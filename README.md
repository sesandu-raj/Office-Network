Office Network Design Project
This project is a practical implementation of a small office network for XYZ Company, a fast-growing global food trading firm headquartered in Eastern Australia. The network was designed to meet the requirements of a new branch in Bonalbo, ensuring scalability, efficient communication, and reliable connectivity.

Project Objectives
To design and implement a network infrastructure that separates the operations of three departments:
Admin/IT
Finance/HR
Customer Service/Reception
To configure VLANs for department-wise segmentation.
To enable inter-department communication while maintaining security and efficiency.
To implement automatic IP address allocation using DHCP.
To integrate wireless connectivity for all departments.
To ensure a robust and scalable design using limited hardware resources.
Technical Details
Hardware Used

Router: 1 Cisco ISR Router
Switch: 1 Cisco Switch
Base Network and Subnetting

Base Network: 192.168.1.0/24
Subnet Mask: 255.255.255.192 (/26)
Subnets:
Subnet 1 (Admin/IT): 192.168.1.0 - 192.168.1.63
Subnet 2 (Finance/HR): 192.168.1.64 - 192.168.1.127
Subnet 3 (Customer Service): 192.168.1.128 - 192.168.1.191
Each subnet supports up to 62 valid hosts.
VLANs

Configured separate VLANs for each department to ensure network segmentation.
DHCP Configuration

Configured DHCP on the router to dynamically assign IP addresses to devices within each VLAN.
Each VLAN has its own DHCP pool to manage IP addressing seamlessly.
Inter-Department Communication

Configured routing on the router to enable devices in different VLANs to communicate while maintaining logical separation.
Wireless Connectivity

Added wireless access points for all departments to provide flexibility for wireless devices.
Skills and Tools Used
Tools: Cisco Packet Tracer
Networking Concepts: VLANs, Subnetting, Routing, and DHCP
Protocols: IPv4, DHCP, and Inter-VLAN Routing
Outcome
This project helped solidify my understanding of networking fundamentals, including:

Designing and segmenting networks using VLANs.
Implementing dynamic IP address allocation with DHCP.
Configuring routing for inter-VLAN communication.
Subnetting and efficient IP address management.
This project is a critical step in my journey toward becoming a proficient network engineer as I pursue my CCNA certification.
