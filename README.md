# IP_Telephony_and_Dial_Peering_Networking_Project






I completed a modest networking project based on a case study in which I used a number of networking concepts, including VLANs, IP addressing, OSPF, VoIP, Dial Peering, Routers, Switchs, SSH, DHCP, Basic Device Settings, Inter-VLAN Routing and Subnetting.





Turtle Consultancy Limited specialised in delivering IT infrastructure solutions to medium sized organizations worldwide. With the expansion of the company, a newly acquired branch needs a network. Your manager is faced with the demands of business and plethora of technology challenges.



You have been recently hired as a Network Engineer and assigned the task of designing and implementing a VoIP network that is based on the requirements and specifications outlined by your manager.





Each group has been assigned the task of designing and implementing a network infrastructure for Turtle Consultancy Limited by internetworking four departments which are as follows :





1) Finance (20 Phones + 20 PCs and 1 printer)




2) HR (20 Phones + 20 PCs and 1 printer)




3) Sales (20 Phones + 20 PCs and 1 printer)





4) ICT (20 Phones + 20 PCs and 1 printer)





All desktop have an associated telephone set(Each PC is connecting directly to a Phone, not a switch).






The network consists of four servers(HTTP,DHCP,DNS,Email) located at the server side site and is fully configured for the operations, and all servers are shared between all users.









Requirements :






The IT Manager emphasized scalibility and availability, and hence you are required to provide a complete network infrastructure design and implementation. Turtle Consultancy Limited will be using the following IP address: 192.168.100.0/24 for Data, 172.16.100.0/24 for Voice and 10.10.10.0/24 between the routers.






1) Design :- Design a network system to meet the given specifications. Use packet tracer software to design your network.






2) Routers :- Each department is to have VoIP enable router with server-side LAN attached to the ICT department router. NOTE :- Use Cisco 2811 router.






3) Switches :- Each department has an access layer switch. NOTE :- Use Cisco 2960 switch.





4) Connections :- Use serial connections between a router and a router, then a straight through cable between the router to switch, switch to hosts, phone to PCs.





5) Subnets :- Each department will be accessing two subnetworks, for example, data and voice subnets. NOTE :- Carry out appropriate subnetting.






6) Basic settings :- Configure basic device settings such as hostnames, console passwords, enable password, banner messages, encrypt all passwords and disable IP domain lookup.






7) DHCP Server :- For Voice(VoIP), use the respective router as the DHCP server while for Data use the DHCP server device at the server-side site.






8) VLANs :- Each department will be in two VLANs. One for data and another for voice. NOTE :- All IP Phones in the network should be in VLAN 100.






9) Inter-VLAN Routing :- Use router-on-a-stick to enable inter-VLAN routing on the network. NOTE :- Create subinterfaces for both data and voice VLANs.






10) IP Addressing :- All the devices in the network are expected to obtain an IP address dynamically from the respective DHCP servers while the devices in the server room are to be allocated IP addresses statically.





11) Routing Protocol :- Use OSPF as the routing protocol to advertise routes on the routers.






12) Remote Access :- Configure SSH in all the routers for remote login.






13) Telephony service :- Configure VoIP on the routers and allocate dial numbers in this format for the department, Finance(1..), HR(2..), Sales(3..) and ICT(4..) (where 1.. can be 101 to 199) and so on.






14) Routing for VoIP :- Configure dial-peering on the routers to allow IP phones from different routers to communicate.







15) Finalize :- Test communication, ensure everything configured is working as expected.





 
Video Demonstration :- https://drive.google.com/file/d/1SMOTgorfjVEUtxpko6f_PUrC9PD1H37J/view?usp=sharing
