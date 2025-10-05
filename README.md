#  Implementation of a Resilient Campus Network with Suricata IDS and ELK SIEM

**Author:** Khaing Zin Thein 
 B.Sc. (Computer Networks), Liverpool John Moores University  
 Completed: June 2025  

---

##  Project Overview
This project focuses on designing and implementing a **secure, fault-tolerant campus network** that integrates **Suricata Intrusion Detection System (IDS)** and the **ELK Stack (Elasticsearch, Logstash, and Kibana)** for **real-time security monitoring** and **centralized log analysis**.

It aims to strengthen the network’s resilience against cyberattacks and improve visibility across different VLAN segments.

---

##  Key Objectives
- Design a **resilient campus network** architecture for 200+ users  
- Implement **VLAN segmentation** and inter-VLAN routing  
- Deploy **Suricata IDS** to monitor and detect malicious traffic  
- Configure **Filebeat + ELK Stack** for log forwarding and visualization  
- Simulate real-world cyberattacks (ICMP flood, Nmap scans, malicious domains)

---

##  Tools & Technologies
- **EVE-NG** – Network emulation  
- **Suricata IDS** – Intrusion detection  
- **Filebeat** – Log shipper  
- **Elasticsearch, Logstash, Kibana (ELK Stack)** – SIEM and visualization  
- **Ubuntu & Kali Linux VMs** – Virtual lab environment  

---

##  System Design
The system was built in **four main phases**:
1. **Virtual Network Design & VLAN Configuration**  
2. **Suricata Deployment on Ubuntu VM**  
3. **Filebeat Setup for Log Forwarding**  
4. **ELK Stack Installation on Kali VM**  

---

##  Testing & Results
- ICMP Echo Requests (Ping)  
- Nmap TCP SYN Scan Simulation  
- Malicious Domain Access Detection  

 **Screenshots:**
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/6c890ed7-3373-4677-bcb8-f8e3b6aae943" />
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/9ed07fe3-a6ae-41da-9831-cc0c57ad0238" />
<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/3810381a-b8c0-4720-9a4f-5ef0d9349034" />


---

##  Key Achievements
- Successfully built a **virtualized and segmented campus network**  
- Integrated **Suricata IDS with ELK Stack** for centralized monitoring  
- Detected simulated network attacks in real time  
- Improved overall **visibility, redundancy, and security posture**

---
