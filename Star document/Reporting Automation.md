---
Created: 2024-04-22
tags: []
Working:
  - Texas Instruments
Tech stack:
  - Python
  - FastApi
  - Nextjs
  - Redux
  - OracleDB
  - JIRA
  - Docker
  - Jenkins
  - Typescript
---
# Problem

* **Manual Reporting Emails:**
    - Previously, the program manager <mark style="background: #FFF3A3A6;">manually sent reporting emails</mark> to higher management three times a week.
        - These emails detailed the team's daily activities, ongoing projects, and the status of tasks (progress, delays, or need for assistance).
        - The content overlapped with information already available in the JIRA space, leading to repetition.
    
- **Limited IT Disruption Communication:**
    - During IT disruptions, only one email was sent to all involved parties.
        - There was no feature to receive continuous updates until the issue was resolved.
        - Managers had to manually check disruption dashboards daily or ask developers for status updates.
    
* There was an opportunity to automate these processes using Atlassian CLI and Python.
# Experience

* **Architecture Design:**
    - Designed a database for configurations needed for JIRA reporting automation.
    - Expanded the database to include other automations, such as IT disruption email notifications.

- **Backend Development:**
    - Connected FastAPI with OracleDB.
    - Integrated with JIRA using Atlassian CLI.
    - Extracted and organized data, exposing it through APIs.
    - Made data extraction configurable.
    - Designed HTML and CSS templates for reporting emails.
    - Created a scheduler for automating report sending via emails.

- **Frontend Development:**
    - Designed TI Templates in Nextjs.
    - Integrated the Redux state management solution.
    - Added authentication using TI Ping and next-auth.

# Results

* **Configuration-Based Application:**
    - Developed an application that can be configured for use by any team facing similar issues.
        - Capable of creating various JIRA and email automations, with dynamic scheduling for reports.

- **Tech Stack Archetype:**
    - Developed a new tech stack archetype for the team's future use.

- **Positive Feedback:**
    - Received positive feedback from senior software developers and managers regarding the reporting automation.
        - Recognised by Ebby Vidyasagar (ITS India VP) and Michael Reynolds (Inventory and Logistics Head).

# Learning

- Learned Atlassian CLI and JQL.
- Acquired knowledge of the new tech stack.
