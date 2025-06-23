# Local_Network_Scanning
A simple network scanning project using Nmap on both Kali Linux and Windows to identify live hosts and open ports in a local network. Useful for beginners learning cybersecurity and ethical hacking.

# 🔍 Nmap Network Scanning Project – Kali Linux & Windows

This project demonstrates how to scan a local network using *Nmap* on both *Kali Linux* and *Windows*, identifying active hosts and open TCP ports. It is part of my cybersecurity learning journey focused on ethical reconnaissance and network exposure analysis.

---

## 🎯 Objective

To discover live hosts and open ports in the local network using a TCP SYN scan (-sS), and understand which services are running on which ports.

---

## 🛠 Tools & Technologies

- 💻 *Operating Systems*: Kali Linux & Windows 11
- 📡 *Tool*: Nmap
- 💬 *Terminal/Command Prompt*: Used to execute Nmap commands
- 🗃 *Text Editor*: Notepad for viewing results
- 🌐 *Git & GitHub*: For version control and project publishing

---

## 📌 Network Details

### Kali Linux Scan:
- *Local IP Range*: 10.2.0.0/24
- *Hosts Detected*: 4 active hosts
- *Open Ports Found*:  
  - 135/tcp → msrpc  
  - 445/tcp → microsoft-ds  
  - Host 10.0.2.15 → all ports closed

### Windows Scan:
- *Local IP Range*: 192.168.224.0/24
- *Hosts Detected*: 2 active hosts
- *Open Ports Found*:  
  - 53/tcp → domain (DNS)  
  - 135/tcp → msrpc  
  - 139/tcp → netbios-ssn  
  - 445/tcp → microsoft-ds
