# Cybersecurity Homelab

## Overview

This repository documents my personal cybersecurity homelab built to gain hands-on experience in networking, system administration, security monitoring, malware analysis, and digital forensics. This lab forms the foundation for future detection, monitoring, and incident response use cases.

The lab simulates a real-world environment with multiple machines, network segmentation, and security tools.

---

## Objectives

* Build a safe environment for cybersecurity practice
* Strengthen networking and system administration skills
* Practice offensive and defensive security workflows
* Centralize logs using Splunk
* Learn malware analysis and DFIR tools

---

## Lab Environment

### Virtualization

* Oracle VirtualBox

### Network & Firewall

* pfSense

### Offensive Security

* Kali Linux

### Vulnerable Machines

* Metasploitable
* Chronos

### Enterprise Environment

* Windows Server (Active Directory)
* Windows 11 Enterprise

### Malware Analysis

* FLARE VM
* REMnux

### DFIR

* Tsurugi Linux

### Monitoring

* Ubuntu + Splunk

---

## Network Diagram

![Network Diagram](diagrams/cyberlab-network-diagram.png)

This diagram illustrates the architecture of the homelab, showing how pfSense segments traffic between the cyber range, enterprise environment, and monitoring systems.


---

## Skills Practiced

* Virtualization
* Network configuration
* Firewall management
* Active Directory setup
* Linux administration
* Log monitoring
* Basic threat detection
* Malware analysis fundamentals
* DFIR fundamentals

---

## Repository Structure

cybersecurity-homelab/
├── docs/
├── diagrams/
├── screenshots/
└── README.md

---

## Screenshots

Screenshots will include:

* Network diagram
* pfSense firewall rules
* VM connectivity tests
* Active Directory setup
* Splunk dashboards
* Security tools setup

---

## Lab Screenshots & Validation

### VirtualBox Lab Environment

![VM List 1](screenshots/network/VM-list-01.png)
![VM List 2](screenshots/network/VM-list-02.png)

These screenshots show all virtual machines used in the lab environment, validating the multi-system setup.

---

### pfSense Firewall Configuration

![Firewall AD Lab](screenshots/pfsense/firewall-rules-ad-lab.png)
![Firewall Cyber Range](screenshots/pfsense/firewall-rules-cyber-range.png)
![Firewall LAN](screenshots/pfsense/firewall-rules-LAN.png)
![Firewall WAN](screenshots/pfsense/firewall-rules-WAN.png)

These demonstrate firewall rules configured in pfSense to control traffic between different network segments.

---

### pfSense Dashboard & Console

![pfSense Dashboard](screenshots/pfsense/pfsense-dashboard.png)
![pfSense Console](screenshots/pfsense/pfsense-console.png)

These validate that pfSense is deployed and functioning as the core firewall/router.

---

### Kali to Metasploitable Connectivity

![Kali Connectivity](screenshots/kali/Metasploitable_ping_in_kali.png)

This confirms successful communication between attacker and target machines.

---

### Active Directory Dashboard

![Active Directory](screenshots/windows-ad/AD-dashboard.png)

This shows the Active Directory setup for centralized identity management.

---

### Splunk Monitoring

![Splunk Homepage](screenshots/splunk/splunk_homepage.png)
![Splunk Forwarder](screenshots/splunk/splunk_forwarder_data.png)

These confirm that Splunk is running and receiving forwarded log data.

---

## Key Learnings

* Understood how to design a segmented network using pfSense
* Gained hands-on experience with firewall rule configuration and traffic control
* Built and managed an Active Directory environment
* Established communication between attacker and target machines
* Deployed Splunk and configured log forwarding
* Learned the importance of visibility and monitoring in a lab environment

---

## Future Improvements

* Improve log forwarding and normalization in Splunk
* Analyze Windows authentication events for suspicious login behavior
* Simulate basic attack scenarios within the lab
* Expand monitoring and detection use cases
* Document investigation workflows and findings


---

## Disclaimer

This lab is created for educational purposes only and is fully isolated.
