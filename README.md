# simulate-a-company-branches-network


Project Overview
This project represents a **complete enterprise-level network topology** built in **Cisco Packet Tracer**.  
It demonstrates how multiple company branches, data centers, and server centers can be interconnected using real-world networking concepts.

The network includes:
- 5 Routers (1 Core Router + 4 Branch Routers)
- Multiple Layer 2 & Layer 3 Switches
- VLANs for segmentation
- DHCP for IP automation
- ACLs for traffic control
- Centralized Data Center and Server Center

⚙️ Technologies Implemented
| Technology | Purpose |
|-------------|----------|
| **OSPF** | Dynamic routing between routers |
| **PPP / Frame Relay** | WAN connectivity simulation |
| **DHCP** | Automatic IP address assignment |
| **VLANs & ACLs** | Network segmentation & security |
| **Trunk Ports** | Carry multiple VLANs across switches |
| **VPN / Label Switching Concepts** | Branch-to-branch connectivity |

🧩 Network Design
- Each building or branch contains multiple VLANs for different departments.
- The **core router** manages routing between all branches via **OSPF**.
- The **multilayer switch** performs **inter-VLAN routing**.
- **DHCP** provides IPs dynamically to all end devices.
- **Access Control Lists (ACLs)** secure communication between departments.


🖥️ How to Open and Run This Project

1️⃣ Download Cisco Packet Tracer
- Go to the official Cisco Networking Academy website:  
  👉 [https://www.netacad.com/portal/resources/packet-tracer](https://www.netacad.com/portal/resources/packet-tracer)  
- Create a free Cisco NetAcad account (if you don’t already have one).
- Download and install **Cisco Packet Tracer**

