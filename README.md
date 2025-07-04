# Airport Network Infrastructure Design

## Overview  
This project presents the design and implementation of a secure and scalable network infrastructure for a modern international airport. The network incorporates multiple networking technologies to ensure efficient communication, optimal resource utilization, inter-departmental connectivity, and high security.

## Objective  
To build a robust airport network infrastructure that meets the operational requirements of various departments by using advanced networking features including:

- VLANs  
- Telnet  
- ACLs  
- Eth-Trunk  
- Static Routing  
- RIP  
- STP  
- DHCP  
- FTP  

## Tools and Technologies  
- **Huawei eNSP**: Used for network simulation and configuration  
- **Switches and Routers**: Layer 2 and Layer 3 devices for interconnectivity  
- **CLI Commands**: For manual configuration of protocols and services  

## Scenario: Department-Wise Network Design  
Each airport department was assigned a specific networking feature to meet its unique operational needs:

| Department                             | Networking Feature Used                  |
|----------------------------------------|-------------------------------------------|
| Airport Operations (Control Room)      | VLANs                                     |
| Financial Services                     | Router-on-a-Stick                         |
| IT Support (Infrastructure & Security) | Static Routing & Telnet                   |
| Data Center (Servers and Storage)      | Link Aggregation (Eth-Trunk)              |
| Customer Services                      | Spanning Tree Protocol (STP)              |
| Human Resource Department              | Subnetting (VLSM)                         |
| Research and Development (Airport R&D) | Routing Information Protocol (RIP)        |
| Airport-wide Public Wi-Fi Access       | DHCP                                      |
| Inter-Departmental Communication       | Inter-VLAN Routing with Layer 3 Switches  |

## Key Features  

- **Network Segmentation** using VLANs for department-wise isolation  
- **Remote Management** enabled through Telnet  
- **Access Control** enforced using ACLs  
- **Bandwidth Optimization** through Eth-Trunk (Link Aggregation)  
- **Redundancy and Loop Prevention** using STP  
- **Dynamic IP Addressing** via DHCP  
- **Routing** using both Static Routing and RIP  
- **Inter-VLAN Communication** for cross-departmental services  
- **File Sharing** using FTP  

## Implementation Steps  

### 1. Network Topology Design  
- Created a modular topology using routers, switches, and end devices  
- Planned IP addressing using subnetting (VLSM) for efficient space utilization  

### 2. Device Configuration  
- Configured VLANs and inter-VLAN routing on Layer 3 switches  
- Set up static and dynamic routing protocols (Static & RIP)  
- Enabled DHCP for Wi-Fi access zone  
- Configured ACLs to control access between departments  
- Applied STP to prevent switching loops  
- Implemented Telnet for router access  

### 3. Testing and Verification  
- Verified connectivity within and across VLANs  
- Tested routing paths, DHCP assignments, and Telnet sessions  
- Validated bandwidth distribution and link redundancy  

## Screenshots  
Included in the PDF:  

- Complete network topology in eNSP  
- VLAN and routing configuration outputs  
- STP convergence and ACL rule verification  
- DHCP pool configuration and dynamic IP assignment  

## Learnings  
- Gained practical experience in enterprise-level network design  
- Learned how to apply different network protocols based on department needs  
- Improved skills in router/switch configuration, subnetting, and redundancy planning  
- Understood the integration of security, scalability, and performance in real-world networks  
