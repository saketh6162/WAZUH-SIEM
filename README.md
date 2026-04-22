# Wazuh SIEM Lab – File Integrity Monitoring (FIM)

## 🔍 Project Description

This project demonstrates the implementation of a Security Information and Event Management (SIEM) lab using Wazuh. The setup includes an Ubuntu-based Wazuh Manager and a Windows-based Wazuh Agent to monitor and detect file system changes in real time.

The primary focus of this project is File Integrity Monitoring (FIM), which enables detection of unauthorized file modifications, deletions, and creations on monitored systems.

## 🧱 Architecture

* **Wazuh Manager:** Ubuntu (Virtual Machine)
* **Wazuh Agent:** Windows Host Machine
* **Network Configuration:** NAT (VMware)
* **Communication Protocol:** Secure agent-manager communication

## ⚙️ Key Features

* Deployment of Wazuh SIEM environment
* Agent registration and secure communication setup
* Real-time File Integrity Monitoring (FIM)
* Detection of file creation, modification, and deletion events
* Visualization of alerts in Wazuh Dashboard

## 🧪 Implementation Workflow

1. Installed and configured Wazuh Manager on Ubuntu
2. Installed Wazuh Agent on Windows system
3. Established agent-manager communication using authentication keys
4. Configured syscheck module for monitoring specific directories
5. Generated test events (file creation/modification/deletion)
6. Analyzed alerts in Wazuh Dashboard

## 🚨 Use Case

The lab simulates real-world scenarios where unauthorized file changes can indicate:

* Malware activity
* Insider threats
* Configuration tampering

## 📊 Outcome

Successfully built a functional SIEM lab capable of detecting and alerting file system changes in real time, providing visibility into endpoint activity.

## 🧠 Skills Demonstrated

* SIEM Deployment & Configuration
* Endpoint Security Monitoring
* Log Analysis & Alerting
* File Integrity Monitoring (FIM)
* Basic Threat Detection Techniques

## 📸 Screenshots

(Add your dashboard, agent status, and FIM alert screenshots here)

## 🚀 Future Improvements

* Integration with threat intelligence feeds
* Alert tuning and rule customization
* Advanced attack simulation (brute force, malware behavior)
