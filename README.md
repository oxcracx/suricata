# Suricata IDS Deployment on Ubuntu Server

This project documents my hands-on implementation of Suricata IDS on an Ubuntu Server.
The goal was to understand how network-based intrusion detection works in a real-world
environment, including rule management, log analysis, and detection tuning.

## Objectives
- Deploy Suricata on Ubuntu Server
- Monitor live network traffic
- Detect reconnaissance attacks (e.g., Nmap scans)
- Customize Suricata rules
- Reduce false positives through tuning

## Environment
- Host OS: Ubuntu (Host Machine)
- IDS Server: Ubuntu Server 22.04
- Network Mode: Bridged 
- Tools: Suricata, Nmap

## Why This Project
Instead of following Suricata documentation directly, this project focuses on:
- Practical troubleshooting
- Understanding why alerts trigger
- Writing and tuning custom rules
