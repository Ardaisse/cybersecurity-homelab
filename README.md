# 🔐 Cybersecurity Homelab – Florian

Personal 24/7 infrastructure focused on SOC, SIEM, Detection Engineering and Cloud Security.

---

## 🎯 Objective

This homelab is designed to simulate a real-world enterprise infrastructure in order to develop practical skills in:

- Security monitoring (SIEM)
- Threat detection
- Incident analysis
- System hardening
- Infrastructure automation

---

## 🏗️ Infrastructure Overview

- Hypervisor: Proxmox VE
- Storage: RAID10 + Proxmox Backup Server (PBS)
- Network: Segmented architecture
- Reverse Proxy: HAProxy
- DNS: PowerDNS

---

## 🔐 Security Stack

### SIEM
- Wazuh
- ELK Stack

### Detection
- Suricata (IDS)
- Zeek

### Threat Hunting / Forensics
- Velociraptor

### Vulnerability Management
- OpenVAS

---

## ⚙️ Infrastructure Services

- Keycloak (IAM)
- Guacamole (secure remote access)
- Samba
- AdGuard
- ClamAV

---

## 🧪 Use Cases

### 1. Network Scan Detection
Detection of suspicious network activity using Suricata, with alert forwarding to Wazuh SIEM.

### 2. Log Analysis & Correlation
Centralized logs analysis and detection of abnormal behavior.

### 3. Linux Hardening
System hardening and monitoring (SSH, services, logs).

---

## 🚀 Future Improvements

- Cloud integration (AWS / Azure)
- Advanced detection rules
- SOAR (Shuffle automation)
