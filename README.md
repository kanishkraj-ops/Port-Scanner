<h1 align="center">🔍 PRT Scanner: Vulnerability Enhanced Edition</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-Cross--Platform-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Use-Ethical%20Hacking-orange?style=flat-square" />
</p>

<p align="center">
  <b>Multi-threaded port scanner with vulnerability info built in</b><br>
  <i>Educational tool to understand open ports, common services, and their misconfigurations</i>
</p>

---

## 📌 Overview

This Python-based port scanner checks specified ports on one or more targets, identifies well-known services (FTP, SSH, RDP, etc.), and displays **vulnerability hints** commonly associated with them. Ideal for **ethical hackers**, **students**, and **pentesters** building foundational skills.

---

## 🚀 Features

✅ Fast multi-threaded scanning  
✅ Scan **multiple IPs** in one go  
✅ Detects common ports & services  
✅ Shows known **vulnerability notes**  
✅ Clean CLI interface with **colorized output**  
✅ Auto-ranged ports: `80`, `1-1000`, etc.  

---

## 🖥️ Demo

```bash
[*] Enter Targets to Scan (comma-separated): 192.168.1.1,192.168.1.5
[*] Enter Ports to Scan (e.g., 80 or 1-1000): 20-100

[*] Starting scan on 192.168.1.1 for ports 20-100...
[+] Port 22 is OPEN on 192.168.1.1
    Service: SSH
    Vulnerability Info: Ensure strong passwords and avoid outdated SSH versions.'''

📦 Setup
1️⃣ Clone the Repository
'''bash
git clone https://github.com/yourusername/portscanner-python.git
cd portscanner-python'''
