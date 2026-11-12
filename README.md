# ITSM & Jira Service Management Lab

## About the Project

This repository documents a hands-on IT Service Management (ITSM) learning project using Jira Service Management and ITIL practices.

The project simulates real-world Service Desk Level 1 (L1) activities, including incident registration, prioritization, escalation, SLA monitoring, and service restoration.

## Technologies and Practices

- Jira Service Management
- ITIL / ITSM
- Incident Management
- Problem Management
- Service Level Agreements (SLAs)
- Jira Query Language (JQL)
- Confluence documentation

## Practical Activities

### Incident Management
- Created and managed incident tickets.
- Classified incidents based on impact and urgency.
- Assigned incidents to support agents.
- Documented troubleshooting and service restoration.
- Resolved incidents after validating service recovery.

### Queues and JQL
Created a queue to monitor unresolved critical incidents.

```sql
issuetype = "[System] Incident"
AND priority IN (Highest, High)
AND resolution = Unresolved
ORDER BY created ASC
```

### SLA Management
- Reviewed first-response and resolution SLAs.
- Studied SLA calendars, targets, and pause conditions.

### Problem Management
- Practiced linking incidents to problem investigations.
- Distinguished service restoration from root cause analysis.

## Practical Case Study

**SUP-6 — SAP Unavailability**

A simulated SAP outage affecting approximately 40 employees and interrupting production.

The exercise included incident classification, assignment, internal documentation, simulated technical escalation, service restoration, and resolution.

The incident was removed from the critical incident queue after its resolution was recorded.

## Project Scope

This is an educational lab project created for professional development. All incident scenarios are simulations and do not represent production incidents at a real company.

## Career Objective

Develop practical skills for Service Desk L1, IT Support, and Junior ITSM roles.
