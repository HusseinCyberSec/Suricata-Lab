# 🔐 Suricata IDS Traffic Analysis & Rule Creation Lab  
**Google Cloud Skills Boost – Exemplar Lab: Examine Alerts, Logs, and Rules with Suricata**

This project demonstrates hands-on SOC analyst skills using **Suricata**, an open-source intrusion detection and prevention system.  
I analyzed packet captures, created and tested custom rules, interpreted IDS alerts, and parsed Suricata’s primary logs: **fast.log** and **eve.json**.

This lab simulates a real-world SOC workflow:  
- Writing detection rules  
- Triggering alerts  
- Parsing logs  
- Understanding network flows  
- Investigating suspicious traffic  

---

# 📸 Screenshots  

### **📷 Suricata Environment Running**
![Suricata Shell]![image alt](https://github.com/HusseinCyberSec/Suricata-Lab/blob/961a50f444884cac19674cc3f2ab2509a6f267e9/1.PNG)

### **📷 Viewing the custom.rules File**
![Custom Rules]![image alt](https://github.com/HusseinCyberSec/Suricata-Lab/blob/961a50f444884cac19674cc3f2ab2509a6f267e9/2.PNG)

### **📷 Suricata Triggering Alerts from sample.pcap**
![Suricata Alerts]![image alt](https://github.com/HusseinCyberSec/Suricata-Lab/blob/961a50f444884cac19674cc3f2ab2509a6f267e9/3.PNG)

### **📷 fast.log Output**
![fast.log]![image alt](https://github.com/HusseinCyberSec/Suricata-Lab/blob/961a50f444884cac19674cc3f2ab2509a6f267e9/4.PNG)

### **📷 eve.json Raw Output (Formatted with jq)**
![eve.json Raw]![image alt](https://github.com/HusseinCyberSec/Suricata-Lab/blob/961a50f444884cac19674cc3f2ab2509a6f267e9/6.PNG)

### **📷 jq Pretty-Printed JSON Output**
![jq Parsed JSON]![image alt](https://github.com/HusseinCyberSec/Suricata-Lab/blob/961a50f444884cac19674cc3f2ab2509a6f267e9/7.PNG)

### **📷 jq Extracting Specific Fields (timestamp, flow_id, signature, proto, dest_ip)**
![jq Field Extraction]![image alt](https://github.com/HusseinCyberSec/Suricata-Lab/blob/961a50f444884cac19674cc3f2ab2509a6f267e9/9.PNG)

---

# 🎯 Lab Objectives

### ✔️ Understand Suricata rule components  
### ✔️ Write and modify IDS signatures  
### ✔️ Trigger alerts using real network traffic (sample.pcap)  
### ✔️ Examine Suricata’s log outputs  
### ✔️ Use jq to extract and correlate alert metadata  
### ✔️ Develop SOC-style incident analysis skills  

---

# 🧠 Scenario Summary  
You play the role of a **Security Analyst** responsible for monitoring internal network traffic.  
You must:

1. Review an existing Suricata rule  
2. Create and modify custom rules  
3. Run Suricata against packet capture traffic  
4. Interpret the resulting logs (fast.log + eve.json)  
5. Use jq to extract alert patterns and event metadata  

This simulates daily SOC tasks such as:
- alert triage  
- network flow correlation  
- signature tuning  
- detection validation  

---


