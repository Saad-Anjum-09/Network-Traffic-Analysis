
# Network Traffic Analysis using Wireshark, tcpdump & Snort 3

## 📌 Project Overview

This project demonstrates the process of capturing, analyzing, and monitoring network traffic using **Wireshark**, **tcpdump**, and **Snort 3** on an Ubuntu 26.04 virtual machine. The objective was to understand how network communication works, analyze different protocols, and detect suspicious activities using a Network Intrusion Detection System (NIDS).

The project covers packet analysis, command-line packet capture, custom Snort rule creation, and detection of network events such as ICMP traffic and TCP SYN (Nmap) scans.

---

## 🎯 Objectives

- Capture live network traffic.
- Analyze common network protocols.
- Understand the TCP/IP communication process.
- Perform packet capture using both GUI and command-line tools.
- Install and configure Snort 3 from source.
- Create custom Snort detection rules.
- Detect ICMP Ping and Nmap SYN Scan activities.
- Improve practical knowledge of network monitoring and intrusion detection.

---

## 🖥️ Lab Environment

| Component | Details |
|-----------|---------|
| Operating System | Ubuntu 26.04 Desktop |
| Virtualization | VMware Workstation |
| Network Interface | ens33 |
| IDS | Snort 3.12.2.0 |
| Packet Analyzer | Wireshark 4.6.4 |
| Command Line Capture | tcpdump |
| Network Scanner | Nmap |

---

## 🛠️ Tools Used

- Wireshark
- tcpdump
- Snort 3
- Nmap
- curl
- ping
- nslookup

---

## 📂 Project Structure

```text
Network-Traffic-Analysis/
│
├── README.md
├── Screenshots/
├── PCAP/
├── Snort/
├── Notes/
├── Report/
└── Resources/
```

---

## 🔬 Project Workflow

### 1. Packet Capture using Wireshark

Captured live network traffic and analyzed:

- DNS
- TCP Three-Way Handshake
- TLS Handshake
- HTTP Traffic

---

### 2. Packet Capture using tcpdump

Captured network traffic from the terminal and saved it into PCAP files for further analysis.

Captured traffic includes:

- DNS
- ICMP
- HTTP
- HTTPS

---

### 3. Snort 3 Installation

- Built Snort 3 from source.
- Configured Snort successfully.
- Validated the configuration.
- Created custom detection rules.

---

### 4. Intrusion Detection

Created custom rules to detect:

- ICMP Ping
- TCP SYN (Nmap Scan)

Generated traffic using:

- ping
- nmap

Successfully detected both events using Snort alerts.

---

## 📖 What I Learned

- Network packet capture
- DNS traffic analysis
- TCP Three-Way Handshake
- TLS handshake process
- Wireshark filtering
- Packet capture using tcpdump
- Snort 3 installation and configuration
- Custom Snort rule creation
- Basic intrusion detection
- Network traffic monitoring

---

## 📸 Project Screenshots

The repository includes screenshots demonstrating:

- Wireshark DNS Analysis
- TCP Three-Way Handshake
- TLS Handshake
- HTTP Traffic
- tcpdump Packet Capture
- Snort ICMP Detection
- Snort Nmap Detection

---

## 🚀 Skills Demonstrated

- Network Traffic Analysis
- Packet Inspection
- Protocol Analysis
- Intrusion Detection
- Snort Rule Writing
- Linux Command Line
- Network Security Fundamentals

---

## 📚 Repository Contents

- Wireshark packet captures
- tcpdump captures
- Snort configuration
- Custom Snort rules
- Project report
- Learning notes
- Useful commands

---

## 🔮 Future Improvements

- Integrate Suricata IDS
- Analyze malware network traffic
- Capture and analyze FTP and SSH traffic
- Visualize traffic using Zeek
- Forward Snort alerts to a SIEM platform

---

## 👨‍💻 Author

**Saad Anjum**

Aspiring SOC Analyst | Threat Detection | Incident Response | Log Analysis | Network Security

---
