# Incident Analysis: Data Loss from Failed Backups

Project for the **Cyber Security and Incident Management** unit of my **Pearson BTEC International Level 3 Extended Diploma in Information Technology** at British Gymnasium of Technology (2024–2025). The diploma was awarded in July 2025 with a triple grade of Merit, Merit, Merit (certificate in `certificate/`).

## The incident

The organisation in the case study kept losing data because its backups were not working reliably: when data needed to be restored, the backup copy was missing or incomplete.

## What I did

1. **Detection:** confirmed the reports of lost data and traced them back to the backup process.
2. **Incident handling:** recorded the impact and what data was affected.
3. **Root cause analysis:** identified the weaknesses in how backups were run, stored and checked.
4. **Problem management:** wrote a remediation plan so the incident would not recur.

## Recommended solution

| Weakness | Recommendation |
|---|---|
| Backups that are run by hand get skipped | Automate backups on a fixed schedule (daily incremental, weekly full) |
| A single backup copy can be lost with the original | Follow the **3-2-1 rule**: 3 copies of the data, on 2 different types of media, with 1 kept off-site or in the cloud |
| Failed backups go unnoticed | Send an alert to IT whenever a backup job fails or is incomplete |
| An untested backup may not restore | Test-restore a sample of files every month and record the result |
| No clear steps when data is lost | Write a short recovery procedure so anyone on the team can restore data |

## Skills shown

Incident handling, root cause analysis, problem management, backup and recovery planning, technical documentation.
