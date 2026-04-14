# suricata-threat-detection-ai
# 🛡️ Network Threat Detection with Suricata & AI

Network threat detection using Suricata IDS with AI-powered alert analysis (SOC simulation lab)

---

## 📌 Project Overview
This project simulates a Security Operations Center (SOC) workflow by detecting network threats using Suricata IDS and analyzing alerts using generative AI.  

Suricata monitors network traffic and generates alerts, while a Python script sends log data to an AI model (Gemini API) to automatically interpret suspicious activity.

---

## 🎯 Objectives
- Deploy and configure Suricata IDS  
- Monitor network traffic and generate alerts  
- Analyze Suricata logs (`eve.json`)  
- Automate alert interpretation using AI  
- Simulate real-world SOC alert triage  

---

## 🧰 Tools Used
- Suricata (Intrusion Detection System)  
- Kali Linux  
- Python  
- Google Gemini API (Generative AI)  
- VirtualBox  

---

## ⚙️ Project Workflow

### 1. Install and Verify Suricata
```bash
sudo apt update
sudo apt install suricata -y
suricata --build-info
## AI Analysis Output

### 🔹 Traffic Generation
![Traffic]<img width="1888" height="936" alt="Screenshot 2026-04-13 150644" src="https://github.com/user-attachments/assets/8db12f83-8b21-4855-8c59-725126a1400b" />


### 🔹 Suricata Logs
![Logs]<img width="1889" height="940" alt="Screenshot 2026-04-13 154524" src="https://github.com/user-attachments/assets/28214a78-3b30-425a-a34d-f142d7283243" />


![AI Output](screenshots/ai-analysis.png)
<img width="1892" height="935" alt="Screenshot 2026-04-13 180940" src="https://github.com/user-attachments/assets/ef7cc9d3-13b9-4989-a129-2c99fdb9ff67" />
