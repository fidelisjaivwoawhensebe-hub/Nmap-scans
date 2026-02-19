# Nmap Network Scanning Labs 🌐🔍

This repository documents my hands-on lab exercises for network scanning, vulnerability discovery, and basic penetration testing techniques.

---

## 🧪 Lab 1: Basic Network Discovery

### 🎯 Objective
Map devices on a target network and identify open ports.

### 🛠 Tools Used
- Nmap (Network Mapper)
- Linux terminal

### 🔎 Investigation Steps
1. Performed ICMP ping sweep to detect live hosts.
2. Scanned for open TCP ports using `nmap -sT`.
3. Identified services running on detected ports.
4. Noted potential targets for further analysis.

### 🚨 Findings
- Multiple hosts active on network.
- Open ports found: 22 (SSH), 80 (HTTP), 443 (HTTPS)
- SSH service accessible, HTTP web service active.

### 🛡 Response Recommendation
- Close unused open ports.
- Harden services (e.g., SSH keys, disable root login).
- Monitor network traffic for anomalies.

---

## 🧪 Lab 2: Advanced Port Scanning & Service Enumeration

### 🎯 Objective
Identify detailed service information on active hosts.

### 🛠 Tools Used
- Nmap (`-sV` and `-O` flags)
- Linux terminal

### 🔎 Investigation Steps
1. Performed version detection scan on live hosts.
2. Collected OS fingerprint information.
3. Analyzed running services and potential vulnerabilities.

### 🚨 Findings
- Web server running outdated Apache version (security patch needed)
- Linux OS detected on host, version 20.04

### 🛡 Response Recommendation
- Update web server to latest version.
- Patch OS vulnerabilities.
- Regularly monitor service versions for security updates.

---

More labs will be added as I continue building hands-on cybersecurity skills in network security and penetration testing.
