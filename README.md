# Pakcet_Tracer_Project_3-


Hi there ! 

Today's project is about VLAN'S , inter-VLANS's Sub-interfaces , subnetting ( 5 subnets) and DHCP configuration in the router 

Equipement : 

- 1 Router 
- 1 Switch 
- 6 PC's (each in a seperate vlan except the first two) 

Tasks done : 

- Cabling 
- Creating Vlans by configuring the Switch 
- Assgining each vlan to it's PC's 
- Configuring port between switch and router as Trunk 
- Configuring router interfaces and sub-interfaces for connection between vlan's 
- Configuring the router as a DHCP server and testing connectivity 

Works like a charm ! you can find an image to check the topology if you don't have packet tracer

Side notes when troubleshooting : 
At first i had an APIPA error when trying to assgin DHCP server so i had the ip 169 ... assigned i re-checked the interface and sub interfaces and found 
that i didn't assgin a default gateway to the inter-vlan interface 

That's it for today ! 
