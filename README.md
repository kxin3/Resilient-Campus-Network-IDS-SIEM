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
 <img width="978" height="513" alt="image" src="https://github.com/user-attachments/assets/0fa2666e-0d6a-4189-84a3-f196a1eb1149" />
 <img width="940" height="598" alt="image" src="https://github.com/user-attachments/assets/7f30d58c-1735-4e51-8599-5e831cfba723" />
<img width="940" height="460" alt="image" src="https://github.com/user-attachments/assets/1d9e1e93-6257-4616-a436-7935e0946fbc" />
<img width="940" height="341" alt="image" src="https://github.com/user-attachments/assets/7d451b9a-09e0-403b-8bec-6089afb70d1a" />

---

##  Key Achievements
- Successfully built a **virtualized and segmented campus network**  
- Integrated **Suricata IDS with ELK Stack** for centralized monitoring  
- Detected simulated network attacks in real time  
- Improved overall **visibility, redundancy, and security posture**

---
