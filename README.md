# Enterprise-Network-Design
CCNA
📡 Enterprise Network Design using Cisco Packet Tracer
📌 Project Overview

This project demonstrates a multi-network enterprise topology built using Cisco Packet Tracer. It includes multiple LANs connected through routers with dynamic routing, redundancy, and inter-VLAN communication.

The design simulates a real-world network with scalability, fault tolerance, and efficient routing.

🧩 Network Features
🔀 Router-on-a-Stick (Inter-VLAN Routing)
🔁 HSRP (Hot Standby Router Protocol) for redundancy
🌐 EIGRP (Enhanced Interior Gateway Routing Protocol) for dynamic routing
🖧 Multiple LAN segments (1.0.0.0, 2.0.0.0, 3.0.0.0, 5.0.0.0)
🔗 Core network (4.0.0.0) connecting all routers
💻 End devices configured with proper IP addressing
🏗️ Network Topology

📊 IP Addressing Scheme
Network	Devices	Example IP
LAN 1	PC0, PC1	1.0.0.x
LAN 2	PC2, PC3	2.0.0.x
LAN 3	PC4, PC5	3.0.0.x
LAN 5	PC6, PC7	5.0.0.x
Core	Routers	4.0.0.x

⚙️ Technologies Used
Cisco Packet Tracer
Routing Protocol: EIGRP
Redundancy Protocol: HSRP
VLAN Routing: Router-on-a-Stick
Switching: Cisco 2950 Switches

🚀 How to Run the Project
Install Cisco Packet Tracer
Download the .pkt file from this repository
Open the file in Packet Tracer
Switch to Simulation Mode (optional) to test packet flow
Use ping commands between PCs to verify connectivity

✅ Testing & Verification
✔️ Ping between different LANs
✔️ Failover testing using HSRP
✔️ Routing verification using:
show ip route
show ip eigrp neighbors
✔️ VLAN communication through router-on-a-stick

📚 Learning Outcomes
Understanding of real-world network design
Implementation of redundancy (HSRP)
Configuration of dynamic routing (EIGRP)
Inter-VLAN communication techniques
Troubleshooting network connectivity

🤝 Contributing

Feel free to fork this repo and improve the topology or add more features like:

OSPF implementation
ACL security
DHCP server configuration

📬 Contact

If you have any questions or suggestions, feel free to connect!
