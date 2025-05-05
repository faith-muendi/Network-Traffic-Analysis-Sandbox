# 🧪 Malware Analysis Sandbox Project

This project demonstrates my hands-on skills in setting up a safe malware analysis lab and performing traffic analysis using tools like Wireshark and PEStudio. The goal is to analyze malware behavior and identify indicators of compromise (IOCs) through static and dynamic methods.

---

## 🔐 Lab Setup

- **Host OS:** Windows 10
- **Virtual Environment:** VMware Workstation
- **Guest OS:** Windows 7 (isolated and not connected to internet)
- **Analysis Tools Used:**
  - PEStudio
  - Process Hacker
  - Procmon
  - Wireshark
  - Autoruns

---

## 💉 Sample Analyzed

- **Malware Sample:** `Bandook` RAT (Remote Access Trojan)
- **File Type:** `.pcap` traffic capture
- **Password:** `infected_19720614` (used to unzip sample safely)

---

---

## 🧠 Key Learnings

- Learned to safely analyze malware without internet exposure.
- Practiced filtering real-world malicious network traffic using Wireshark.
- Understood how malware uses DNS to communicate with command-and-control (C2) servers.

---

## 📊 Wireshark Network Traffic Analysis

The following image shows analysis of suspicious DNS traffic by the malware:


- **Suspicious Domain Queried:** `
- **Protocol:** DNS
- **Behavior Observed:** The malware attempted to resolve multiple domains with high entropy and random characters, typical for C2 communication.

## 📁 screenshots


![malicious_capt](https://github.com/user-attachments/assets/53b95ca8-6f93-454c-b869-3942a0cfe390)
![ip_packets](https://github.com/user-attachments/assets/ddf46199-effe-4a8d-97f8-77c9d0249909)
![dnspackets](https://github.com/user-attachments/assets/7ffd3e9e-5d90-457e-9ae1-72a15e6016b5)
