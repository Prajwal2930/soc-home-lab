# 👨‍💻SOC Home Lab: Attack & Defense Simulation 🚀

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Network Topology](#network-topology)
4. [Step 1: Setting Up Virtual Machines](#step-1-setting-up-virtual-machines)
5. [Step 2: Installing Splunk for Log Monitoring](#step-2-installing-splunk-for-log-monitoring)
6. [Step 3: Installing Sysmon on Windows 10](#step-3-installing-sysmon-on-windows-10)
7. [Step 4: Generating Malware with msfvenom](#step-4-generating-malware-with-msfvenom)
8. [Step 5: Setting Up a Metasploit Listener](#step-5-setting-up-a-metasploit-listener)
9. [Step 6: Monitoring Logs with Splunk](#step-6-monitoring-logs-with-splunk)
10. [Troubleshooting](#troubleshooting)
11. [Next Steps & Future Improvements](#next-steps--future-improvements)
12. [How to Contribute](#how-to-contribute)
13. [Conclusion](#conclusion)

---
## 📌Introduction
This project demonstrates the setup of a home lab environment for cybersecurity testing, including an attack machine (Kali Linux), a target machine (Windows 10 VM), and a logging system (Splunk) to monitor malicious activities. The project involves:

- Setting up isolated virtual machines.

- Installing and configuring Sysmon for comprehensive log collection.

- Generating and deploying malware using msfvenom.

- Monitoring attacks using Splunk for analysis and detection.

Note: This lab is for educational purposes only. All activities should be conducted in a strictly isolated environment to prevent any unauthorized access or damage to your personal network or data. Do not use these techniques for unauthorized activities.

## 🔧 Prerequisites

| Requirement           | Description                                                                 |
| :-------------------- | :-------------------------------------------------------------------------- |
| RAM                   | At least 16GB (to comfortably run multiple VMs simultaneously).             |
| Virtualization Software | VMware Workstation (Pro/Player) or VirtualBox. Ensure you are familiar with basic VM operations. |
| Operating Systems     | ISO files for Windows 10 (a non-N edition is generally recommended for broader compatibility) and Kali Linux. |   
| Logging Tools         | Splunk Enterprise (Free/Trial version for home lab) and Sysmon setup files, along with a pre-configured `sysmonconfig.xml`. |
| Internet Connection   | Required for downloading ISOs, tools, updates, and configuration files.     |
| Disk Space            | At least 100GB of free disk space for VM images and logs.                   |