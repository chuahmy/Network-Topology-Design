# 🌐 Cisco Multi-Site Enterprise Network Design

## 📌 Overview

This project demonstrates the design and implementation of a **secure, scalable multi-site enterprise network** using Cisco Packet Tracer.

The network connects **Kuala Lumpur (HQ)** with branch offices in **Australia, Singapore, and India**, ensuring reliable communication, high availability, and strong security across all locations.

---

## 🏗️ Network Architecture

* Multi-site hierarchical network design
* Centralized **Server Farm (India)**
* Combination of **LAN, WAN, and WLAN** infrastructure
* Redundant links for high availability

---

## ⚙️ Key Features

### 🔹 Network Segmentation

* Implemented **VLANs** to separate departments and control traffic
* Configured **Inter-VLAN Routing** for communication between VLANs
* Used **VLAN 999 (Blackhole)** for unused ports (security purpose)

### 🔹 IP Addressing

* Designed using **VLSM (Variable Length Subnet Masking)**
* Efficient IP allocation for scalability
* Separate addressing for LAN, WAN, and Server Farm

---

## 🌐 Routing & Connectivity

* Configured **OSPF (Open Shortest Path First)** for dynamic routing
* Implemented **default static routes** for route optimization
* Established full **WAN connectivity between all sites**

---

## 🔄 Redundancy & Performance

* Implemented **HSRP (Hot Standby Router Protocol)** for gateway redundancy
* Configured **EtherChannel** for:

  * Increased bandwidth
  * Link aggregation
  * Fault tolerance

---

## 📡 Wireless Network

* Designed WLAN for branch offices
* Used **Wireless LAN Controller (WLC)**
* Applied **WPA2 Enterprise security** for secure access

---

## 🖥️ Server Farm Services

Centralized services hosted in India:

* 🌍 DNS Server
* 🌐 Web Server
* 📁 FTP Server

---

## 🔐 Security Implementation

### 🔹 Layer 2 Security

* Port Security
* DHCP Snooping
* Dynamic ARP Inspection (DAI)

### 🔹 Attack Mitigation

Tested and protected against:

* MAC Address Flooding
* DHCP Spoofing
* VLAN Hopping
* STP Attacks

---

## 🧪 Additional Configurations

* Configured **802.1Q trunking** with restricted VLAN access
* Secured devices using:

  * Console & VTY passwords
  * Password encryption
  * Login banners
* Implemented **DHCP services** for automatic IP assignment

---

## 🖼️ Network Topology

<img width="626" height="436" alt="Full_Topology_Design" src="https://github.com/user-attachments/assets/9e3642fc-16c7-433a-b924-6116a43ce313" />


```
Full_Topology_Design.png
```

---

## 📂 Project Files

* `Full_Topology_Design_noPassword.pkt` → Cisco Packet Tracer file
* `Full_Topology_Design.png` → Network diagram screenshot
* `network-design-report.pdf` → Project documentation

---

## 🚀 Tools Used

* Cisco Packet Tracer
* Networking Concepts (Routing & Switching Essentials)

---

## 📊 Project Outcome

* Successfully built a **fully functional multi-site enterprise network**
* Achieved **secure, scalable, and fault-tolerant design**
* Verified connectivity, routing, and security across all sites

---

## 👨‍💻 Author

**Chuah Ming Yuan**

* Computer Science Student (Cybersecurity)
* Passionate about Networking & Security

---
