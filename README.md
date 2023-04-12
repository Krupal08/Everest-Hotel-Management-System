# Hospital Network Design in Packet Tracer

################################## **Topology Details** ##################################

1) Router On Each Floor, Placed in Server Room of IT Dept.

2) All Router (2911) connected with Serial DCE Cable.

3) Network between Router – 10.10.10.0 – 10.10.10.4 – 10.10.10.8 with /30.

4) Each Floor have a Switch (2960).

5) Each Floor have Wi-Fi network (AP-PT) count to laptop and phones.

6)  Printer on Each Department.

################################## **Configuration** ##################################

7) Used OSPF to advertise routes.

8) Used DHCP in Each Router to Dynamically Allocate IP on Each Device.

9) All Device in the network can communicate with each other.

10) Configured SSH in each Router for Remote Login.

11) Added PC/Laptop in IT department to PORT fa0/2 for Test Remote Login.

12) Configured PORT SECURITY to IT Dept Switch to allow only TEST-PC to Access Port fa0/2
(used sticky method to get mac-add with violation mode to shut down.
