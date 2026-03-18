**🔐 CyberDefenders Labs Writeups**

Welcome to my CyberDefenders Labs Reposiroty 👩‍💻
This repository contains detailed writeups of cybersecurity challenges completed on the CyberDefenders platform, focusing on Digital Forensics, Incident Response, Threat Hunting, and Blue Team operations.

**📌 About Me**

I am an Information Security & Forensics Analyst with hands-on experience in:

* Digital Forensics

* Network Traffic Analysis

* Incident Response

* Threat Detection & Investigation

This repository reflects my practical skills in analyzing real-world security scenarios.

**🎯 Objectives**

* Strengthen Blue Team and DFIR skills

* Practice real-world cyber incident investigations

* Document methodologies and tools used in analysis

* Build a portfolio for cybersecurity roles

## 🧪 Labs Covered (SOC / DFIR Tracking)
## 🧪 Labs Covered

| Lab Name             | Category           | Tools Used              | MITRE ATT&CK Technique              | Description                                   |
|---------------------|--------------------|------------------------|--------------------------------------|-----------------------------------------------|
| PoisonedCredentials | Network Forensics  | Wireshark, tcpdump     | T1556 – Modify Authentication Process| Analyzed compromised credentials in a network capture |
| SPAN Sniff          | Network Forensics  | Wireshark              | T1046 – Network Service Discovery    | Investigated mirrored network traffic for anomalies |
| Gamer Case          | Disk Forensics     | Autopsy, FTK, Strings  | T1078 – Valid Accounts               | Recovered evidence from disk image to track insider misuse |
| Memory Leak         | Memory Forensics   | Volatility             | T1055 – Process Injection            | Identified malicious processes injected in memory |
| Log Analysis 101    | SIEM / Logs        | Splunk, ELK            | T1110 – Brute Force                  | Detected brute-force login attempts from system logs |
| Phishing Attack     | Incident Response  | Email Header Analyzer  | T1566 – Phishing                     | Investigated phishing emails and analyzed headers |
| Malware Traffic     | Network Forensics  | Wireshark, Zeek        | T1071 – Application Layer Protocol   | Detected command-and-control traffic in PCAP capture |
| Web Attack Logs     | Web Security       | Burp Suite, Logs       | T1190 – Exploit Public-Facing App    | Analyzed web server logs for injection attacks |
| Ransomware Incident | Incident Response  | Volatility, Autopsy    | T1486 – Data Encrypted for Impact    | Investigated ransomware infection and affected systems |
| DNS Exfiltration    | Network Forensics  | Wireshark, tcpdump     | T1048 – Exfiltration Over Alt Prot.  | Detected data exfiltration via DNS tunneling |
| Suspicious Login    | SIEM / Logs        | Splunk                 | T1078 – Valid Accounts               | Tracked unusual login patterns for unauthorized access |
| Malware Dropper     | Malware Analysis   | Strings, PEStudio      | T1204 – User Execution               | Analyzed a malware dropper to understand its behavior |
| ARP Spoofing        | Network Forensics  | Wireshark              | T1557 – Adversary-in-the-Middle      | Detected ARP poisoning attempts on the network |
| Privilege Escalation| Incident Response  | Logs, Linux CLI        | T1068 – Privilege Escalation         | Investigated unauthorized privilege escalation activity |
| Suspicious Process  | Memory Forensics   | Volatility             | T1059 – Command Execution            | Identified suspicious processes running in memory |
| Data Exfiltration   | Network Forensics  | Wireshark, Zeek        | T1041 – Exfiltration Over C2         | Detected large outbound data transfers to suspicious hosts |
| Brute Force Attack  | SIEM / Logs        | Splunk                 | T1110 – Brute Force                  | Monitored repeated login attempts for potential brute force |
| Backdoor Detection  | Malware Analysis   | Strings, IDA           | T1543 – System Process Modification  | Analyzed malware backdoor and system modifications |
| Lateral Movement    | Incident Response  | Logs, Wireshark        | T1021 – Remote Services              | Tracked attacker lateral movement across hosts |
| Suspicious DNS      | Network Forensics  | Wireshark              | T1071.004 – DNS                      | Investigated abnormal DNS queries for data tunneling |
⚠️ Note: Writeups do not include flags where restricted, in compliance with platform policies.

**🛠️ Tools & Technologies**

🐧 Linux (Kali)

📡 Wireshark

🧠 Volatility Framework

🔍 Autopsy

🧾 tcpdump

🧬 Strings & Hex Analysis

🌐 OSINT Techniques

**📂 Repository Structure**
CyberDefenders-Labs/
│
├── Network-Forensics/
│   ├── Lab-Name/
│   │   ├── writeup.md
│   │   └── screenshots/
│
├── Memory-Forensics/
├── Malware-Analysis/
└── Incident-Response/

**🧠 Methodology**

Each lab follows a structured investigation approach:

- Understanding the Scenario

- Evidence Identification

- Data Analysis

- Tool Application

- Findings & Conclusion

**🚀 Key Skills Demonstrated**

- Packet analysis & traffic inspection

- Log analysis and event correlation

- Memory and disk forensics

- Malware behavior analysis

- Threat detection & reporting

**📸 Sample Analysis**

Screenshots and evidence are included in each lab folder to support findings and demonstrate the investigation process.

**⚠️ Disclaimer**

This repository is for educational purposes only. All labs are completed within legal environments provided by CyberDefenders.

## 🤝 Connect With Me

💼 LinkedIn: [Deborah Nyatichi](https://www.linkedin.com/in/deborah-nyatichi-886b04206)

📧 Email: [binyanyadeborah770@gmail.com](mailto:binyanyadeborah770@gmail.com)

**⭐ Support**

If you find this repository useful, feel free to:

⭐ Star the repo

🍴 Fork it

📢 Share with others in the cybersecurity community
