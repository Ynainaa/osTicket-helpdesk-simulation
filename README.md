# osTicket-helpdesk-simulation
**Platform: **Windows + XAMPP + osTicket 1.18
**Mail Alerts:** Configured via SMTP relay
**Author:** Lucy Wainaina

## Overview
Simulated a full IT helpdesk environment using osTicket. Demonstrated ticket logging, assignment, escalation, SLA enforcement, canned responses, email alerts, and reporting.

## Repository structure
- `screenshots/` — dashboard and workflow images
- `reports/` — exported CSVs (tickets_by_department.csv, sla_escalation_events.txt)
- `logs/` — simulated logs and exported DB events
- `config_notes/` — installation/config commands & notes
- `portfolio/` — PDF project report

## How to reproduce (summary)
1. Install XAMPP on Windows
2. Extract osTicket to `C:\xampp\htdocs\osticket`
3. Create DB `osticketdb` and run installer
4. Configure departments, SLAs, canned responses, email (SMTP)

### 🧰 Skills Demonstrated
- IT Support Workflow Simulation  
- SLA Management & Ticket Escalation  
- SQL Reporting (custom queries)  
- Troubleshooting osTicket installations (Windows/XAMPP)  
- User and Role Administration  

## Sample Screenshots
![Email Alert](screenshots/Email_alert.PNG)

![Critical Incident Response](screenshots/critical_incident_response.PNG)

![Help Topics](screenshots/help_topics.PNG)

![SLA Settings](screenshots/SLA.PNG)

## Sample Report
Below is a snapshot from the dashboard
![Dashboard Report](screenshots/Report.PNG)

It shows ticket activity for the period **Nov 2–5, 2025**:
| Help Topic | Opened | Assigned | Overdue | Closed |
|-------------|--------|-----------|----------|--------|
| General Inquiry | 1 | 1 | 0 | 1 |
| Report a Problem | 1 | 3 | 1 | 1 |
| Password Reset | 1 | 2 | 0 | 1 |
| Network Connectivity | 1 | 1 | 0 | 1 |
| Email Account Setup | 2 | 1 | 0 | 1 |
| Server Downtime | 1 | 1 | 0 | 1 |

**PDF Summary:**
[Helpdesk Project](portfolio/helpdesk_simulation_project.pdf)
