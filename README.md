# 🛡️ Traffic Network PCAP Threat Hunting & Analysis (Self-Learning Project)

![SOC](https://img.shields.io/badge/SOC-Threat_Hunting-blue) ![Wireshark](https://img.shields.io/badge/Wireshark-PCAP_Analysis-green) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-orange) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Summary

This self-initiated cybersecurity project simulates a **real-world cyberattack** on a city's traffic light management system using a publicly sourced PCAP file. The purpose was to practice **network forensics**, **threat hunting**, and **SOC-level analysis** from start to finish.

🔍 I acted as a **Security Operations Center (SOC) analyst**, performing:

- Network traffic investigation
- Threat actor profiling
- Attack chain mapping using MITRE ATT&CK
- Development of bash-based defensive mitigations
- Reporting of key findings in a structured format

> **Note**: This is a purely educational & ethical project. All data used is either simulated or sourced from open-access cybersecurity learning resources.

---

## 🧠 Learning Objectives

- Apply real-world SOC methodologies to investigate attacks
- Detect reconnaissance, exploitation, and lateral movement in PCAP
- Perform deep packet inspection using **Wireshark**
- Map attack steps to **MITRE ATT&CK** framework
- Write defensive **bash scripts** for immediate mitigation
- Document findings in a professional report

---

## 🛠️ Tools & Technologies Used

| Category               | Tool / Framework           |
|------------------------|----------------------------|
| Network Analysis       | Wireshark                  |
| Scripting              | Bash (Linux Terminal)      |
| Threat Modeling        | MITRE ATT&CK               |
| Report Writing         | Microsoft Word & PDF       |
| Presentation           | PowerPoint (for visual summary) |
| GitHub                 | Version Control & Hosting  |

---

## 📂 Project Structure

Traffic_Network_pcap-threat-hunting/
│
├── 📁 Pcap/ # PCAP files used for analysis
├── 📁 Report/ # Technical report (PDF & DOCX)
├── 📁 PPT/ # Project summary slides
├── 📁 Screenshot/ # Wireshark packet analysis screenshots
├── 📁 Mitigation_Script/ # Bash script for threat mitigation
├── 📄 README.md # This file


---

## 📊 Key Findings

- **Initial Access**: Phishing email via SMTP
- **Credential Theft**: Unencrypted HTTP POST login
- **Reconnaissance**: TCP SYN port scanning from multiple IPs
- **Remote Code Execution**: SSH exploit for C2 setup
- **DNS Tunneling**: Covert communication channel
- **API Hijacking**: Internal pivot via API manipulation
- **DDoS Attempt**: 36,000+ SYN flood packets
- **Final Objective**: Access to traffic control SQL database

🧠 Each stage of the attack was **mapped to MITRE ATT&CK techniques** and backed by PCAP evidence.

---

## 🛡️ Bash-Based Defense Script

A custom bash script was written to:

- Block malicious IPs via `iptables`
- Detect SYN flood attempts
- Log abnormal network activity
- Auto-mitigate threats

📁 Script: `Mitigation_Script/threat_mitigation.txt.txt`  
📸 Screenshots included in `Screenshot/`

---

## 🎓 What I Gained

- **SOC-level experience** in incident response simulation  
- Hands-on **Wireshark and packet analysis** skills  
- **MITRE-based attacker profiling & kill chain reconstruction**  
- Experience writing **technical documentation & reports**  
- Confidence to perform **threat hunting on real-world traffic**

---

## 🚀 How to Use

1. Clone this repo:
```bash
git clone https://github.com/amnaamjid/Traffic_Network_pcap-threat-hunting.git
Open the .pcap file in Wireshark

Follow the report or screenshots for insights

Run the bash script in a Linux terminal (test environment recommended)



💬 Connect With Me
📧 amnaamjid002@gmail.com
🔗 LinkedIn – https://www.linkedin.com/in/amna-amjid-a6b800251/
🌐 GitHub – (https://github.com/amnaamjid)
