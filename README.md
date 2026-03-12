## SecOps Lab

A hands-on **Security Operations (SecOps) lab** that simulates real-world web attacks against OWASP Juice Shop and monitors them using the **ELK Stack (Elasticsearch, Logstash, Kibana)**.

The project focuses on **attack simulation, log ingestion, detection rule development, and MITRE ATT&CK mapping** to demonstrate practical detection engineering workflows.

Project Documentation - https://png270.github.io/posts/elk-juice-shop/

### Project Overview

This lab environment generates web application attack telemetry and analyzes it using a centralized logging pipeline.


#### Key Features

- Simulate **OWASP Top 10 web attacks**
- Ingest and analyze logs using the **ELK stack**
- Build **detection rules in Kibana**
- Map attacks to **MITRE ATT&CK techniques**
- Visualize alerts and attack activity through dashboards
- CI pipeline with **GitHub Actions for config validation**

#### Tech Stack

- OWASP Juice Shop
- Elasticsearch
- Logstash
- Kibana
- Filebeat
- Docker
- GitHub Actions

#### Lab Objectives

- Understand how web attacks appear in application logs
- Develop practical detection rules for common attack patterns
- Map detections to the MITRE ATT&CK framework
- Build a lightweight SIEM-style monitoring environment

#### Future Plan

- Detection rules + MITRE mapping
- Suricata + OWASP ZAP
- Wazuh + Vault
- SOAR script 

---

This repository is intended for **learning and experimentation**. Work in progress.

