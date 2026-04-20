# 🌆 Smart City Network Simulation (Cisco Packet Tracer)

## 📌 Overview
This project presents a **Smart City Network Simulation** designed using Cisco Packet Tracer. It demonstrates how multiple city services such as Government, Banking, Traffic, Public WiFi, and CCTV Surveillance can be integrated into a single network while maintaining proper segmentation, communication, and security.

The project uses modern networking concepts like **VLAN, Inter-VLAN Routing, Wireless Networking, and ACL Security** to simulate a real-world smart city infrastructure.

---

## 🎯 Objectives
- Design a structured smart city network  
- Implement VLAN segmentation for different departments  
- Enable communication using Inter-VLAN Routing  
- Configure Wireless Network (WiFi) using SSID & password  
- Apply ACL (Access Control List) for security  
- Test network connectivity and restrictions  

---

## 🏗️ Network Architecture
The network follows a hierarchical design:

- Core Switch → Central connection point  
- Main Router → Handles routing between VLANs  
- Access Switches → Connect different departments  

### VLAN Structure:
| VLAN ID | Network      | IP Range          |
|--------|-------------|------------------|
| 10     | Government  | 192.168.10.0/24  |
| 20     | Bank        | 192.168.20.0/24  |
| 30     | Traffic     | 192.168.30.0/24  |
| 40     | WiFi        | 192.168.40.0/24  |
| 50     | CCTV        | 192.168.50.0/24  |

---

## ⚙️ Technologies Used
- Cisco Packet Tracer  
- VLAN (Virtual LAN)  
- Inter-VLAN Routing (Router-on-a-Stick)  
- Wireless Networking (SSID & WPA2 Security)  
- Access Control List (ACL)  

---

## 📶 Wireless Network
- SSID: **SmartCityWiFi**  
- Security: **WPA2-PSK**  
- Usage: Public access (citizens)  
- Configured as Access Point  

---

## 🔐 Security Implementation (ACL)

Example ACL configuration:

## Bash
access-list 101 deny ip 192.168.30.0 0.0.0.255 192.168.10.0 0.0.0.255
access-list 101 permit ip any any

---

## 📸 Screenshots

### Network Topology
![Topology](https://github.com/Abhishekcoder711/City_Network_Configuration/blob/main/Network%20Topology/Network%20Topology.png)

---

## 🚀 Key Features
- VLAN-based network segmentation  
- Inter-VLAN routing using Router-on-a-Stick  
- Wireless network setup (SSID & Password)  
- ACL-based network security  
- Scalable smart city network design  
- Real-world network simulation  

---

## 📚 Learning Outcomes
- Understanding of VLAN and segmentation  
- Practical implementation of routing  
- Network security using ACL  
- Wireless network configuration  
- Network testing using ping commands  
- Hands-on experience with Cisco Packet Tracer  

---

## 👨‍💻 Author
**Abhishek Kumar Mishra**  
MCA – Chandigarh University  
