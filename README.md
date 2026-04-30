# 🛡️ AI-DefenceX ✅

Wazuh-based Security Monitoring and Threat Detection project deployed on Ubuntu Server with Suricata integration and automated email alerts.

## 🚀 Overview

AI-powered security monitoring system using Wazuh and Suricata with automated threat detection and response.

## 🧠 AI Detection Engine

Custom Python-based anomaly detection system leveraging behavioral analysis and traffic pattern modeling:

- Detects unusual traffic patterns
- Identifies suspicious IP behavior
- Supports automated threat scoring
- Triggers response actions (alerts + IP blocking)

This enhances traditional SIEM systems by introducing intelligent anomaly-based threat detection.

## 🏗️ Architecture

Distributed Systems → Tailscale (Secure Mesh VPN) → Suricata (IDS) → Wazuh (SIEM) → Python AI Detection Engine → Threat Detection → Alert Generation → Email Notification → Automated Response (IP Blocking via iptables)

### 🔍 Detection Capabilities:
- Port scanning detection
- Brute force attack detection
- DNS tunneling detection
- Suspicious tools (nmap, sqlmap, hydra, metasploit)
- File Integrity Monitoring (FIM)

### ⚡ Automated Response:
- Real-time alert generation
- Email notifications
- Automatic IP blocking using iptables
- MITRE ATT&CK mapping

## Features

- Installed and configured Wazuh server on Ubuntu
- Integrated Suricata IDS for network threat detection
- Designed and configured Suricata monitoring dashboard
- Custom rule tuning and alert monitoring
- Automated email notifications for triggered alerts
- Security event visibility through Wazuh dashboard
- Log monitoring and incident detection

## Tech Stack

Wazuh, Suricata, Ubuntu Server, Linux, SIEM, Email Alerts

## 📊 Project Screenshots

### 🛡️ Wazuh Dashboard
![Wazuh](images/images_wazuh-dashboard.jpg)

### 📊 Wazuh Overview
![Wazuh Overview](images/images_wazuh-dashboard-overview.jpg)

### 🌐 Suricata Dashboard
![Suricata](images/images_suricata-dashboard.jpg)

### 📈 Suricata Overview
![Suricata Overview](images/images_Suricata-dashboard-overview.jpg)

### 📡 Suricata Monitor
![Monitor](images/images_suricata-monitor.jpg)

### 📜 Security Logs
![Logs](images/images_security-logs.jpg)

### 🚨 Alerts
![FIM](images/images_fim-alert.jpg)
![Suricata Alert](images/images_suricata-alert.jpg)
![Windows Event](images/images_windows-event-alert.jpg)

## 👤 Author

**Rushikesh Babhulkar**  
🔗 GitHub: https://github.com/rushikeshb-cyber  
📧 Email: rbabhulkar448@gmail.com
