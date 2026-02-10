# Lab 3: Local Network Discovery & Host Enumeration Using Kali Linux and Nmap

## 📌 Lab Overview
This lab demonstrates how to identify local network configuration and discover active hosts within a virtual network environment. Kali Linux and Windows 10 virtual machines are used to analyze IP addressing, routing, host availability, and service information using Netdiscover and Nmap.

---

## 🛠 Task A: Identify Local Network Configuration

### On Kali Linux

#### Steps Performed
- Opened terminal with root privileges
- Checked network interface configuration
- Identified IP address of `eth0`
  - IP Address: **192.168.91.128**
- Displayed routing table using:
```bash
ip route show
