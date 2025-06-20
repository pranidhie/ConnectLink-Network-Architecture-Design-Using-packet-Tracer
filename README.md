# ConnectLink-Network-Architecture-Design-Using-packet-Tracer

🖧 Connect Link Network Design Project
📍 Introduction
Connect Link operates across a three-floor office building, with each floor dedicated to a specific department. To support efficient daily operations, the company needs a reliable, secure, and scalable network design. This project outlines the planning, design, and simulation of such a network using Cisco Packet Tracer.

Each floor is equipped with its own switch and hosts unique sets of users. The network is segmented using VLANs, interlinked using routers, and includes DHCP services, port security, and remote access to ensure smooth and secure communication.

🎯 Project Objectives
The main goals of the project are:

Segmented Network: Each department has its own VLAN to separate traffic and reduce broadcast domains.

Inter-VLAN Routing: Communication between departments is enabled through a router-on-a-stick setup while maintaining security boundaries.

Centralized IP Management: IP addresses are dynamically assigned using DHCP pools to reduce manual configuration errors.

Secure Remote Access: Router management is enabled through SSH, offering encrypted access to authorized admins.

Access Control: Unauthorized devices are blocked using port security.

Hierarchical Modular Design: The network is designed in layers (access, distribution, core) to support better organization and future scalability.

🧭 Scenario Overview
The building has 3 floors, each assigned to a different department:

Floor 1: Admin Department

Floor 2: IT Department

Floor 3: Finance Department

Each floor is connected via its own Layer 2 switch.

All switches are connected to a central router that manages VLAN routing and external connections.

Static routes and OSPF (if applicable) are configured for proper network reachability.

🛠️ Technologies Used
Cisco Packet Tracer 8.x

VLANs

DHCP Configuration

SSH Configuration

Access Control Lists (ACLs)

Port Security

Static Routing / OSPF

Router-on-a-Stick Inter-VLAN Routing


📈 Future Improvements
Implement a redundant router for high availability.

Add network monitoring tools like SNMP or NetFlow.

Include wireless access points and mobile device security.

Expand the network to support remote branches.

✅ Conclusion
This project demonstrates a practical implementation of networking concepts, ensuring secure and efficient communication in a multi-department organization. With proper planning and a modular approach, Connect Link is now prepared to scale its operations with confidence.

