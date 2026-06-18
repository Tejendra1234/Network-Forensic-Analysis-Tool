# Network Forensic Analysis Tool

## Overview

A Python-based network forensic analysis tool designed to assist in monitoring, detecting, and investigating suspicious network activities.

The project includes multiple security monitoring modules that can be used for network visibility, incident investigation, and basic threat detection.

---

## Features

### Packet Capture
Captures network packets for traffic analysis and forensic investigations.

### ARP Spoofing Detection
Monitors ARP traffic and detects potential ARP spoofing attacks.

### Data Exfiltration Monitoring
Detects abnormal outbound traffic patterns that may indicate data exfiltration attempts.

### Credential Detection
Analyzes network traffic for potential credential exposure and sensitive information leakage.

---

## Technologies Used

- Python
- Scapy
- Packet Analysis
- Network Monitoring
- Digital Forensics
- Cybersecurity

---

## Usage

```bash
python main.py -m capture
python main.py -m arp
python main.py -m exfiltration
python main.py -m credentials
