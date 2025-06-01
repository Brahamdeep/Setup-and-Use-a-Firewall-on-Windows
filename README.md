# 🔥 Setup and Use a Firewall on Windows

This project demonstrates how to configure and test basic firewall rules using **Windows Defender Firewall**. The objective is to understand how to allow and block traffic through specific ports using inbound rules.

---

## 🛠️ Objectives

- Block Telnet traffic (port 23)
- Allow SSH traffic (port 22)
- Test firewall behavior using command-line tools
- Document and understand how Windows Firewall filters traffic

---

## 📋 Steps Performed

1. Opened **Windows Defender Firewall with Advanced Security** (`wf.msc`)
2. Created a new **Inbound Rule** to **block TCP port 23 (Telnet)**
3. Tested using:
   telnet localhost 23
   → Connection was blocked
4. Created a rule to allow TCP port 22 (SSH)
5. Deleted the block rule to restore the original firewall state
