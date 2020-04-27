# YoSIEM

This is a repository for A SIEM platform using curated Open Source Tools. 

The SIEM platform consists of the following components:

Component               |         Purpose
---                     |       ---
NXLogs  | Shipping Windows Event Logs to Syslog Server
Rsyslog | Shipping Linux Logs to syslog Server
Syslog-Ng | Ingest logs, parse, enrich, format and Send to Elasticsearch. 
Elasticsearch | Store Log Data from Syslog , WAZUH
Kibana | Web Interface to interact with SIEM data. 
Wazuh | Intrusion Detection and Prevention System for Windows and Linux Hosts. 
Grafana | Dashboards, Charts and Alerting from Data in ElasticSearch

Installation Instructions and Scripts for Automatic Installation Coming Soon !
