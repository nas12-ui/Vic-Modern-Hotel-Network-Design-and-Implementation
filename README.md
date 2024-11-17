Vic Modern Hotel Network Project
Project Overview
This project involves the design and implementation of the Vic Modern Hotel Network, which spans across three floors and includes various departments with distinct VLANs. The network is built using Cisco Packet Tracer to simulate the hotel’s internal network infrastructure. The aim of this project is to set up a fully functional network with the necessary configurations to ensure proper communication between departments and floors, following the requirements listed in the problem statement.

Network Design
The network design for Vic Modern Hotel includes three floors, with each floor having its own set of departments. Each department is assigned to a different VLAN, and there are routers connecting the floors, facilitating inter-department communication.

Floor Layout and VLAN Assignments
1st Floor:
Reception: VLAN 80, Network: 192.168.8.0/24
Store: VLAN 70, Network: 192.168.7.0/24
Logistics: VLAN 60, Network: 192.168.6.0/24
2nd Floor:
Finance: VLAN 50, Network: 192.168.5.0/24
HR: VLAN 40, Network: 192.168.4.0/24
Sales/Marketing: VLAN 30, Network: 192.168.3.0/24
3rd Floor:
Admin: VLAN 20, Network: 192.168.2.0/24
IT: VLAN 10, Network: 192.168.1.0/24
Network Components
Routers:

Three routers are placed in the server room in the IT Department. These routers are connected via serial DCE cables using the following networks:
10.10.10.0/30
10.10.10.4/30
10.10.10.8/30
OSPF routing protocol is used to advertise routes between routers for efficient communication.
Switches:

One switch is placed on each floor to connect all devices (computers, printers, phones, etc.) within the respective departments.
WiFi Networks:

Each floor has a Wi-Fi network providing connectivity to laptops and phones in all departments.
Printers:

Each department has one printer connected to the respective VLAN.
VLAN Configuration:

Each department is assigned a separate VLAN, which helps in segmenting the network traffic and improving network efficiency.
Configuration
OSPF Routing Protocol
The OSPF (Open Shortest Path First) protocol is configured on the routers to allow dynamic routing between the routers and advertise the routes for all departments across the floors.

VLAN Configuration
Each department is assigned to a specific VLAN. The VLANs are configured on the switches and routers to ensure that devices in each department can communicate within their VLAN but remain isolated from other VLANs unless routing is enabled.

IP Addressing
The IP addressing scheme follows the subnetting as specified in the problem statement. Static IP addresses are assigned to devices within each department according to their respective VLANs and networks.
WiFi and Device Configuration
Each department is connected to the respective VLAN and provides wireless access to laptops and phones via access points configured on the switches.

Printer Configuration
Printers are connected within each department, and the devices (e.g., computers, laptops) are configured to send print jobs to the respective printers.

