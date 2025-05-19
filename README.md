# 🛡️ Intrusion Detection System with Snort & Wazuh

This project showcases the deployment and integration of an **Intrusion Detection System (IDS)** using **Snort** and **Wazuh** for real-time network monitoring and alerting.

---

## 📘 Project Overview

In this project, I configured **Snort** to detect suspicious network traffic and integrated it with the **Wazuh SIEM platform** to analyze, correlate, and visualize logs for better threat detection and response.

---

## 🎯 Objectives

- Deploy and configure Snort on a Linux-based system
- Detect common network attacks (e.g. port scans, DNS tunneling)
- Forward Snort alerts to Wazuh for SIEM analysis
- Use Wazuh dashboards to visualize IDS alerts in real time

---

## 🧱 Technologies Used

- **Snort** – Open-source Network IDS
- **Wazuh** – Security Information & Event Management (SIEM)
- **Linux (Ubuntu)** – Host environment
- **Wireshark** – Packet capture and traffic analysis
- **Syslog** – For log forwarding

---

## 🖥️ Setup Overview

1. **Install Snort**
   - Configure network interface
   - Enable alert rules (e.g. for Nmap scans, brute force)

2. **Install Wazuh**
   - Use Wazuh agent to collect logs
   - Forward Snort logs to Wazuh manager

3. **Log Integration**
   - Use `barnyard2` or custom syslog config
   - Parse logs in Wazuh for dashboards and alerts


