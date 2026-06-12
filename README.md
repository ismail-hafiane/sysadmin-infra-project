# Automated Infrastructure — Ansible + Docker + Zabbix on Azure

## Overview
Automated deployment of a monitored infrastructure on Azure using:
- **Ansible** — configuration management & deployment automation
- **Docker** — containerized services (Nginx, web app)
- **Zabbix** — monitoring, alerting & NOC dashboard
- **Azure** — cloud infrastructure (2 Ubuntu VMs)

## Architecture
| VM | Role | Services |
|---|---|---|
| app-server | Application | Docker, Nginx, Web App, Zabbix Agent |
| monitoring-server | Monitoring | Zabbix Server, Zabbix Frontend |

## Project Status
🟡 In progress — Sprint 0 : Infrastructure setup

## Author
Ismail Hafiane — NOC Analyst → SysAdmin/DevOps
[LinkedIn](https://www.linkedin.com/in/ismailhafiane7/)
