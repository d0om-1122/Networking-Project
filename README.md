# XYZ Company Branch Network – Cisco Packet Tracer Project

This project designs and implements a network for XYZ Company’s new branch in Bonalbo using Cisco Packet Tracer.  
It fulfills the company’s VLAN, wireless, and connectivity requirements using one router and one switch.

---

## 🧩 Network Overview

- **Base Network:** 192.168.1.0/24  
- **VLANs:**
  - VLAN 10 – Admin/IT: 192.168.1.0/26
  - VLAN 20 – Finance/HR: 192.168.1.64/26
  - VLAN 30 – Customer Service/Reception: 192.168.1.128/26
- **Router:** Cisco 2911 (Inter-VLAN routing)
- **Switch:** Cisco 2960
- **Wireless Access:** Access Points for each VLAN
- **DHCP:** Configured on router for automatic IPv4 assignment
- **Inter-VLAN Communication:** Enabled via router sub-interfaces

---

## 🧠 Key Features
- Automatic IP addressing using DHCP
- Inter-VLAN routing configured on router
- Wireless network per department
- Devices successfully tested for connectivity across VLANs

---

## 📂 Files
- `small_office_project.pkt` – Main Cisco Packet Tracer file
- `ping-tests/` – Connectivity verification screenshots
- `screenshots/` – Network topology and problem statement
- `docs/` – Extra notes or configurations

---

## ✅ Results
All departments can communicate across VLANs successfully.  
Ping tests confirm correct DHCP assignment and routing configuration.
