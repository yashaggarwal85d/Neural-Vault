---
Created: 2024-04-22
tags: []
Working:
  - Texas Instruments
Tech stack:
  - Plsql
  - OracleDB
  - Docker
---
# Problem

* TI used two vendor applications, Demand manager and Input optimiser (DM/IO), and wanted to replace them with a single in-house application.
    - This required extensive expertise in these applications and deep domain knowledge in Demand management.
- Several Z-jobs were running to populate data between the two tools.
    - One of these jobs, ZOPP562A, frequently failed.
    - Previous attempts to resolve this issue were unsuccessful in identifying the root cause.
    - The frequent failures in Z-jobs were one of the reasons for replacing the two tools.

# Experience

* The Z-Jobs were written in PlSql, making it essential to learn this language.
* ZOPP562A core issue was found after a deep dive into the ocean of scripts and tables.
* Fixing the issue was surprisingly simple, involving only the NULL values of some entries in a table.
- A basic proof-of-concept application for the replacement was developed.
- The project was later terminated due to:
    - Reduction in job failures.
    - Lack of domain knowledge expertise in the team.
    - Change in team priorities.
    - Mass layoffs in the Philippines.
# Results

* Fixing the Z-Job error provided <mark style="background: #BBFABBA6;">significant relief for the team</mark>.
    - Failures occurred twice every week.
    - Managed services personnel had to report the error and perform repeated steps to fix it.
        - More than 40% of the time, the issue was not resolved, requiring a developer from our team to be available.
    - Saved weekend work for many people.

# Learning

* Acquired proficiency in PlSQL.
- **Gained domain knowledge in demand management** and input optimisation.
- <mark style="background: #FFB86CA6;">Recognised that some efforts are destined to fail, but that doesn't diminish their value.</mark>
