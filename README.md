# SOC Home Lab — Threat Detection & Incident Response

## Project Overview
Built a complete SOC home lab environment to simulate
and detect real cyber attacks using industry standard tools.

## Tools Used
- Kali Linux — Attack simulation
- Wazuh v4.14.3 — Endpoint Detection and Response
- Splunk Enterprise — SIEM and Log Analysis
- Security Onion — Network Monitoring

## Lab Setup
- Kali Linux VM — Attacker machine
- Wazuh OVA — Security monitoring server
- Windows VM — Target machine
- All running on VirtualBox

## Attack Scenarios Simulated
- Port Scanning using Nmap
- Brute Force Attack using Hydra
- SSH Attack simulation
- Password Guessing attacks

## Results Achieved
- 1368 Authentication failures detected
- 586 Total security alerts generated
- Brute Force attacks successfully detected
- MITRE ATT&CK techniques mapped

## MITRE ATT&CK Mapping
| Attack | Technique ID |
|--------|-------------|
| Port Scan | T1046 |
| Brute Force | T1110 |
| SSH Attack | T1021 |
| Password Guessing | T1110.001 |
| Credential Access | T1078 |

## Screenshots
All screenshots available in repository

## Skills Demonstrated
- SOC environment setup
- SIEM configuration and management
- Endpoint detection and response
- Attack simulation and detection
- Log analysis and correlation
- MITRE ATT&CK framework mapping
- Incident response documentation
