# Lab 01 – Wazuh SIEM Fundamentals & Initial Setup

📄 **Full Detailed Documentation (with screenshots & steps):**  
([Wazuh Fundamentals.pdf](https://github.com/MSafwanAwan/Wazuh-Setup/blob/5f2bbee3b8269ab06618e74df6b710fe2216644d/Wazuh%20Fundamentals.pdf))


## 📌 Objective
This lab focuses on building a foundational understanding of **Wazuh SIEM** through initial deployment, agent integration, monitoring configuration, and basic threat detection in a simulated SOC environment.



## 🧩 Lab Coverage

### 1.1 Introduction to Wazuh SIEM
- Overview of SIEM concepts  
- Wazuh architecture: Manager, Agent, Dashboard  
- Role of centralized log collection and monitoring  

### 1.2 Wazuh Server Installation
- Installed Wazuh Manager, Indexer, and Dashboard  
- Verified all core services were running  

### 1.3 Static IP Configuration
- Assigned static IP to Wazuh server  
- Ensured persistence across reboot  
- Verified connectivity via ping and dashboard access  

### 1.4 Agent Deployment (Linux & Windows)
- Installed and registered Linux agent via Dashboard  
- Installed and registered Windows agent via CLI  
- Verified agent status and communication  

### 1.5 File Integrity Monitoring (FIM)
- Enabled FIM on Linux and Windows agents  
- Monitored custom directories  
- Detected file creation, modification, and deletion  

### 1.6 Windows Defender Log Integration
- Collected Defender logs via Windows Event Channel  
- Simulated malware detection using EICAR test file  
- Verified alerts in Wazuh Dashboard  

### 1.7 Dashboard Navigation & Visualization
- Explored built-in dashboards  
- Created custom visualization for alert analysis  

### 1.8 SSH Brute Force Detection & Active Response
- Simulated SSH brute-force attack  
- Detected failed login attempts  
- Configured firewall-drop active response  
- Verified attacker IP blocking  



## 🛠️ Tools & Technologies
- Wazuh SIEM  
- Linux (Ubuntu)  
- Windows  



## 🎯 Skills Gained
- SIEM deployment and configuration  
- Agent installation and management  
- Log monitoring and alert analysis  
- File Integrity Monitoring (FIM)  
- Brute-force attack detection  
- Active response automation  
- SOC dashboard analysis  



## Advanced Resources
- [Wazuh Documentation](https://documentation.wazuh.com/)
- [Wazuh Community](https://wazuh.com/community/)
- [Wazuh on GitHub](https://github.com/wazuh/wazuh)

Feel free to reach out for help or contribute to the Wazuh community!
