# CODEALPHA_IDS

## Network Intrusion Detection System

### Internship Domain
Cybersecurity + Network Security

---

## Project Description
This project is a Network Intrusion Detection System (NIDS) developed during the CodeAlpha Cybersecurity Internship using Snort/Suricata.

The system monitors live network traffic and detects suspicious or malicious activities based on predefined security rules and intrusion detection signatures.

The project helps in understanding:
- Network traffic monitoring
- Intrusion detection mechanisms
- Packet inspection
- Threat analysis
- Security alert generation

---

## Technologies Used
- Snort / Suricata
- Python
- Wireshark
- Linux / Kali Linux

---

## Features
- Real-Time Network Traffic Monitoring
- Intrusion Detection and Alerts
- Custom Detection Rules
- Packet Analysis
- Threat Logging
- Network Security Monitoring

---

## Objectives
- Detect suspicious network activity
- Analyze malicious traffic patterns
- Monitor network packets continuously
- Generate alerts for potential attacks
- Improve network security awareness

---

## Detection Rules Implemented
- ICMP Ping Detection
- Port Scan Detection
- Suspicious TCP Traffic Detection
- Unauthorized Access Attempts
- Malware Communication Alerts

---

## Project Structure

```text
CODEALPHA_IDS/
│
├── rules/
│   └── local.rules
│
├── logs/
│
├── screenshots/
│
├── README.md
│
└── setup_guide.txt
```

---

## Installation

### Install Snort

```bash
sudo apt update
sudo apt install snort
```

---

## Running Snort

```bash
sudo snort -A console -q -c /etc/snort/snort.conf -i eth0
```

---

## Example Custom Rule

```text
alert icmp any any -> any any (msg:"ICMP Ping Detected"; sid:1000001; rev:1;)
```

---

## Sample Alert Output

```text
[**] [1:1000001:1] ICMP Ping Detected [**]
[Priority: 0]
04/07-10:30:20.123456
```

---

## Tools Used
- Snort
- Suricata
- Wireshark
- Kali Linux

---

## Learning Outcomes
- Understanding intrusion detection systems
- Working with Snort/Suricata rules
- Monitoring network packets
- Detecting suspicious activities
- Improving network defense strategies

---

## Future Improvements
- Web Dashboard Integration
- Real-Time Threat Visualization
- Email Alert System
- Machine Learning Threat Detection
- Automated Response Mechanisms

---

## Author
AKULA GOWRI GEETHIKA SAI SRIJA

Cybersecurity Intern at CodeAlpha

---

## License
This project is for educational and internship purposes.
