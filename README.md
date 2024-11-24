# Hotel-Management-Project
The project aimed to enhance efficiency and security in the Hotel Management Network, utilizing OSPF, inter-VLAN routing, traffic segmentation, and secure remote management. It also implemented SSH access, IP subnetting, and port security.
HOTEL MANAGEMENT PROJECT USING PACKET TRACER

Project Requirement: 
You are required to design and implement Hotel Network. The Hotel has Three floors, in the first floor there are three departments, 
        1) Reception 
        2) Store
        3) Logistics
In the Second floor there are three departments 
1)	Finance
2)	HR
3)	Sales and Marketing
While the Third floor has the IT and Admin. Therefore, the following are the part of the considerations during the design and implement. 
1)	There should be three routers connecting each floor
2)	All routers should be connected each other using DCE Serial cable. 
3)	The network between the routers should be 10.10.10.0/30, 10.10.10.4/30, 10.10.10.8/30
4)	Each floor is expected to have one switch(placed in respective floor) 
5)	Each department is expected to have a printer. 
6)	Each department is expected to have WIFI networks connected to laptops and phones. 
7)	Each department is expected to be in different VLAN with the following details, 

1st Floor: 
•	Reception – VLAN 80, Network of 192.168.8.0/24
•	Store – VLAN 70, Network of 192.168.7.0/24
•	Logistics – VLAN 60, Network of 192.168.6.0/24

2nd Floor: 
•	Finance – VLAN 50, Network of 192.168.5.0/24
•	HR – VLAN 40, Network of 192.168.4.0/24
•	Sales – VLAN 30, Network of 192.168.3.0/24

3rd Floor: 
•	Admin – VLAN 20, Network of 192.168.2.0/24
•	IT – VLAN 10, Network of 192.168.1.0/24
8)	Use OSPF as the routing protocol to advertise routes. 
9)	All devices in the network are expected to obtain IP address dynamically with their respective router configured as the DHCP server. 
10)	All the device in the network is expected to communicate with each other.
11)	Configure SSH in all the routers for remote login
12)	In the IT department, add PC called the Test PC to port Fa0/2 and use it to test remote login. 
13)	Configure port security to IT-dept switch to allow only Test -PC to access port fa0/2. (use sticky method o obtain mac address with violation mode of shutdown).
Network Topology: 
 



