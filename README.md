# Firewall-Setup-and-Configuration
Setup and Use a Firewall on Windows | Configured Windows Defender Firewall rules to block Telnet (port 23), allow SSH (port 22), and tested filtering.

# Task 4 – Setup and Use a Firewall on Windows

## 📌 Objective
Configure and test basic firewall rules on **Windows Firewall** to allow or block network traffic.

---

## ⚙️ Steps Performed

### 1. Listed Current Firewall Rules
- Opened `wf.msc` (Windows Defender Firewall with Advanced Security).
- Viewed **Inbound Rules** list.  

<img width="1320" height="895" alt="Screenshot 2025-09-27 132907" src="https://github.com/user-attachments/assets/bce9276c-aece-45b5-87d7-c3b85fe66320" />

---

### 2. Blocked Telnet (Port 23)
- Created new inbound rule:
  - Type: **Port**
  - Protocol: **TCP**
  - Port: **23**
  - Action: **Block the connection**
  - Applied to: Domain, Private, Public
- Rule named: **Block Telnet (Port 23)**


<img width="922" height="185" alt="Screenshot 2025-09-27 133950" src="https://github.com/user-attachments/assets/fbeaf59a-4799-494f-a5d6-710593bb48f6" />

Tested using:
```cmd


