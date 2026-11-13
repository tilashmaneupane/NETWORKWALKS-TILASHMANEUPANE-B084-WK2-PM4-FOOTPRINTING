
# Penetration Testing: Footprinting & Network Scanning 🔍

**Program**: Cybersecurity Internship at Networkwalks  
**Module**: Week 2 (W2-PM-FINAL)  
**Author**: Tilashma Neupane  

## 📝 Project Overview
This repository contains the documentation, methodologies, and findings from the Week 2 Footprinting and Network Scanning modules. The project focuses on utilizing open-source intelligence (OSINT) and active scanning techniques to map target attack surfaces. 

The exercises demonstrate the progression from gathering public intelligence without directly touching a target environment, to actively mapping out live infrastructure and topology on a local area network.

## 🛠️ Tools & Technologies
* **theHarvester**: Used for passive reconnaissance to gather corporate emails, sub-domains, and infrastructure details from public search engines and databases.
* **Zenmap (Nmap GUI)**: Used for active network scanning to discover live hosts, IP allocations, and MAC addresses on a local subnet.
* **Kali Linux**: Primary penetration testing environment.
* **Windows CMD**: Used for local network configuration enumeration.

## 🚀 Modules Completed

### 1. W2-PM4: Reconnaissance with theHarvester
* **Target Scope**: `microsoft.com` (Educational Scope)
* **Objective**: Extract valid corporate email addresses and surface hidden sub-domains using public data sources (e.g., Baidu). 
* **Key Learning**: Understanding how passive OSINT feeds into targeted phishing campaigns and password spraying attacks without alerting the target.

### 2. W2-PM5: Network Scanning with Zenmap
* **Target Scope**: Local LAN Network
* **Objective**: Perform a localized Ping scan to identify active devices, retrieve hardware MAC addresses, and generate a visual network topology graph.
* **Key Learning**: Mapping internal network structures to identify potential targets for subsequent aggressive port scanning and vulnerability assessment.

## 📂 Repository Contents
* `Penetration_Testing_Report_W2-PM-FINAL.pdf`: The complete formal penetration testing report containing detailed findings, risk analysis, and security recommendations.
* `/Evidences`: Folder containing screenshots of terminal outputs, theHarvester results, and the Zenmap topology graph.

## ⚠️ Liability Disclaimer
**For Educational Purposes Only.** 
All activities documented in this repository were performed strictly on systems where authorized permission was secured or on personally owned devices/local networks. Unauthorized access or testing is a crime. The author is not responsible for the misuse of this information or any resulting damage. 
