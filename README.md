# Everest ![Everest network topology](https://user-images.githubusercontent.com/72334419/235166760-9c7ee571-ba9e-4042-90e7-c0c7423fd090.png)
Hotel Network Design in Packet Tracer
Design and implement Vic Modern Hotel network. The hotel has three floors & each floor has department with VLANs as follows:

<n>1st Floor:</n>
- Reception- VLAN 80, Network of 192.168.8.0/24
- Store- VLAN 70, Network of 192.168.7.0/24
- Logistics- VLAN 60, Network of 192.168.6.0/24

<n>2nd Floor:</n>
- Finance- VLAN 50, Network of 192.168.5.0/24
- HR- VLAN 40, Network of 192.168.4.0/24
- Sales- VLAN 30, Network of 192.168.3.0/24

<n>3rd Floor:</n>
- Admin- VLAN 20, Network of 192.168.2.0/24
- IT- VLAN 10, Network of 192.168.1.0/24

################################## **Topology Details** ##################################

- There should be three routers connecting each floor (all placed in the server room in IT department).
- All routers should be connected to each other using serial DCE cable.
- The network between the routers should be 10.10.10.0/30,10.10.10.4/30 and 10.10.10.8/30.
- Each floor is expected to have one switch (placed in the respective floor).
- Each floor is expected to have WIFI networks connected to laptops and phones.
- Each department is expected to have a printer.
- Use OSPF as the routing protocol to advertise routes.
- All devices in the network are expected to obtain IP address dynamically with their respective router configured as the DHCP server.
- All the devices in the network are expected to communicate with each other.
- Configure SSH in all the routers for remote login.
- In IT department, add PC called Test-PC to port fa0/1 and use it to test remote login.
- Configure port security to IT-dept switch to allow only Test-PC to access port

<b>Technologies Implemented:</b>

- Connecting Networking devices with Correct cabling.
- Creating VLANs and assigning ports VLAN numbers.
- Subnetting and IP Addressing.
- Configuring Inter-VLAN Routing (Router on a stick).
- Configuring DHCP Server (Router as the DHCP Server).
- Configuring SSH for secure Remote access.
- Configuring switchport security or Port-Security on the switches.
- Configuring WLAN or wireless network (Cisco Access Point).
- Host Device Configurations.
- Test and Verifying Network Communication.
