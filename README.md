# 🛡️ Mini SOC Setup – Wazuh SIEM Project

This project sets up a basic home Security Operations Center (SOC) using a pre-configured Wazuh SIEM virtual machine. The goal was to explore log monitoring, dashboard access, and the foundation of real-world cybersecurity tools.

---

## 🧠 Project Purpose

- Learn how Security Information & Event Management (SIEM) systems work
- Access and explore a Wazuh dashboard in a home lab setup
- Simulate what SOC analysts use to track and investigate security events
- Prepare for future steps: log collection, agent connection, and alerting

---

## 🛠 Tools Used

- **VirtualBox** – to run VMs
- **Wazuh OVA (v4.1.12)** – pre-built Linux-based SIEM appliance
- **Terminal / Bash** – to interact with the Wazuh VM and find the IP
- **Browser** – to access Wazuh’s web UI via local IP

---

## 🔐 Steps Taken

1. Imported the **Wazuh .ova** file into VirtualBox  
2. Launched the VM and waited for boot to complete  
3. Logged in using:
   - `Username: wazuh-user`  
   - `Password: wazuh`  
4. Ran `ip a` inside the VM to find the local IP address  
5. Entered the IP (e.g. `https://192.168.1.23`) into my main computer's browser  
6. Logged into the Wazuh dashboard using:
   - `Username: admin`  
   - `Password: admin`  
7. Explored the dashboard tabs: overview, rules, agents, events, and system health

---


## 💡 Key Learnings

- Successfully set up and accessed a local SIEM dashboard
- Understood how security logs and events are visualized in a SOC environment
- Gained confidence navigating terminal commands in Linux
- Prepared for connecting a Windows machine to forward logs in the next project

---

## ✅ Next Step

[ ] Configure a **Windows VM agent** to send logs to Wazuh  
[ ] Simulate login failures or alerts and track them in the dashboard  
[ ] Analyze event data for suspicious behavior (security event analysis)


