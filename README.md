# Splunk Enterprise Lab

A hands-on cybersecurity and SIEM lab documenting the installation, configuration, data ingestion, SPL queries, Windows log analysis, and dashboard development using Splunk Enterprise on Linux.

## Project Overview

This project demonstrates practical experience with Splunk Enterprise as a Security Information and Event Management (SIEM) platform.

The lab focuses on understanding how logs are collected, indexed, searched, analyzed, and visualized using Splunk and Search Processing Language (SPL).

## Objectives

* Install Splunk Enterprise on Linux
* Understand the Splunk architecture and directory structure
* Configure Splunk Enterprise
* Create and manage indexes
* Ingest log data
* Learn Search Processing Language (SPL)
* Analyze Windows event logs
* Perform basic security log analysis
* Create dashboards and visualizations
* Develop practical SIEM and SOC-related skills

## Environment

| Component        | Details                            |
| ---------------- | ---------------------------------- |
| Operating System | Kali Linux                         |
| Platform         | Linux x86_64                       |
| SIEM             | Splunk Enterprise                  |
| Query Language   | SPL                                |
| Primary Use      | Security Monitoring & Log Analysis |

## Repository Structure


Splunk-Enterprise-Lab/
│
├── 01-Installation/
├── 02-Configuration/
├── 03-Data-Ingestion/
├── 04-SPL-Query-Cookbook/
├── 05-Windows-Event-Logs/
├── 06-Dashboards/
└── Screenshots/


## Project Progress

* [x] Splunk Enterprise installation
* [x] Splunk configuration
* [x] Index creation
* [x] Data ingestion
* [x] Basic SPL queries
* [x] Advanced SPL queries
* [x] Windows event log analysis
* [x] Dashboard creation

## SPL Queries Covered

The project will document practical SPL commands including:

index=*
index=main
index="windowslogs"
| table
| sort
| reverse
| stats
| fieldsummary
| chart


Additional searches and commands will be added as the lab progresses.

## Skills Demonstrated

* Splunk Enterprise
* SIEM
* SPL
* Linux Administration
* Log Analysis
* Windows Event Log Analysis
* Security Monitoring
* Dashboard Development
* SOC Fundamentals

## Learning Outcome

This project is intended to demonstrate hands-on experience with Splunk Enterprise and practical SIEM workflows, from initial installation and configuration to log investigation and visualization.

## Author

Rubesh Gokula Kannan M

Cyber Security Student
