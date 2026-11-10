# Courier Office Multi-Department Network

A secure, scalable, and redundant multi-department office network designed and simulated using **Cisco Packet Tracer**.
<img width="708" height="231" alt="image" src="https://github.com/user-attachments/assets/7b12d835-0121-40a1-9022-6808369fac12" />

## 📌 Project Overview

This project focuses on designing and implementing a computer network infrastructure for a Courier Office. The network connects multiple departments through VLAN segmentation, provides centralized network services, and ensures reliable internet connectivity using two ISPs.

The network is designed to provide secure communication, efficient resource sharing, centralized management, and high availability.

## 🎯 Objectives

- Design a segmented network for a courier office.
- Connect all departmental devices securely.
- Implement VLANs for network segmentation.
- Configure DHCP for automatic IP address allocation.
- Configure OSPF for dynamic routing.
- Provide redundant internet connectivity through two ISPs.
- Implement port security for sensitive departments.
- Provide centralized services through a dedicated server room.
- Test connectivity, routing, and failover mechanisms.

## 🏢 Network Departments & VLAN Configuration

| VLAN ID | Department | Network Devices |
|---|---|---|
| 10 | HR | PC, Printer, Access Point |
| 20 | Sales | PC, Printer, Access Point |
| 30 | Finance | PC, Printer, Access Point |
| 40 | Admin | PC, Printer, Access Point |
| 50 | ICT | PC, Printer, Access Point |
| 60 | Server Room | DHCP, DNS, Email Servers |

**Note:** Port Security is enabled for the Finance Department to restrict unauthorized devices.

## 🛠️ Technologies & Protocols

- Cisco Packet Tracer
- Cisco IOS
- VLAN (Virtual LAN)
- OSPF (Open Shortest Path First)
- DHCP (Dynamic Host Configuration Protocol)
- DNS (Domain Name System)
- NAT (Network Address Translation)
- Port Security
- Telnet
- WPA2/WPA3 Wireless Security

## 🌐 Network Services

| Service | Description |
|---|---|
| DHCP Server | Automatically assigns IP addresses to devices. |
| DNS Server | Resolves hostnames into IP addresses. |
| Email Server | Supports internal email communication. |
| Internet Access | Provides connectivity through two ISPs. |
| Printer Sharing | Enables departmental printer access. |
| Wireless Connectivity | Provides Wi-Fi access through Access Points. |
| Network Monitoring | Supports traffic monitoring and troubleshooting. |

## 🔐 Security Implementation

- VLAN segmentation to isolate departmental traffic.
- Port Security to prevent unauthorized device connections.
- Maximum one device per secured port with restrict violation mode.
- WPA2/WPA3 wireless security.
- Router password protection using enable secret.
- MOTD banner configuration.

## 🔄 Redundant Internet Connectivity

The network uses two ISP connections to improve availability.

- **ISP1:** Primary internet connection.
- **ISP2:** Backup internet connection.

OSPF is configured to support dynamic routing and default-route propagation. If the primary internet path fails, the backup path can be used.

## 🧪 Testing & Verification

The following network functionalities were tested:

- PC-to-PC connectivity using ping.
- PC-to-server connectivity.
- DHCP address allocation.
- DNS name resolution.
- Email server connectivity.
- Internet connectivity through the primary ISP.
- Backup connectivity during primary path failure.
- Finance VLAN port security.
- Departmental printer connectivity.

## 👥 Project Team

**University:** Sir Syed University of Engineering & Technology (SSUET)  
**Department:** Software Engineering  
**Course:** Computer Communication & Networks (SWE-306)  
**Semester:** 5th  
**Batch:** 2023F  
**Section:** F  

| Team Member | Roll Number |
|---|---|
| Syed Muhammad Azan | 2023F-BSE-272 |
| Muhammad Safwan | 2023F-BSE-282 |
| Shaheer Abbasi | 2023F-BSE-289 |
| Isbah Ali | 2023F-BSE-266 |

**Submitted To:** Sir Fayyaz Ali

## 📂 Project Files

The repository can contain:

- Cisco Packet Tracer simulation file (`.pkt`)
- Project report (`.pdf`)
- Network topology screenshots
- Configuration screenshots

## 🎓 Learning Outcomes

Through this project, we gained practical experience in:

- Network topology design.
- VLAN configuration and management.
- Inter-VLAN communication.
- Dynamic routing using OSPF.
- DHCP and DNS server configuration.
- Network security and port security.
- ISP redundancy and failover.
- Network troubleshooting using Cisco Packet Tracer.

## 📜 License

This project was developed for academic and educational purposes as part of the Computer Communication & Networks course at SSUET.

---

**Developed with Cisco Packet Tracer | SSUET Software Engineering Department**
