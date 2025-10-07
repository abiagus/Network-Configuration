
# DHCP Server with Inter-VLAN Routing – Cisco Packet Tracer Project

This project shows how to configure a DHCP server and enable inter-VLAN communication using Cisco Packet Tracer. It simulates a small enterprise network where multiple departments (VLANs) automatically receive IP addresses from a central DHCP server, while routers handle communication between the VLANs.

---

## Project Explanation

The aim of this project was to build a secure and scalable local area network that supports automatic IP management and communication between departments through a central router.

The network is divided into different VLANs such as Admin, HR, Sales, and Guest. Each VLAN is assigned a separate subnet and configured to receive IP addresses automatically from the DHCP server. A router-on-a-stick setup is used to route traffic between VLANs, and trunk links carry multiple VLANs between switches and the router.

Key steps carried out:

1. Created VLANs on switches and assigned ports to each VLAN.
2. Configured trunk links between switches and routers.
3. Created subinterfaces on the router using 802.1Q encapsulation.
4. Configured DHCP server pools for each VLAN with their respective gateways.
5. Connected PCs to VLAN ports and tested automatic IP allocation.
6. Verified communication between VLANs using ping and traceroute.

---

## Concepts Used

* VLANs were used to logically separate departments for better performance and security.
* Inter-VLAN routing was implemented using the router-on-a-stick method.
* DHCP was configured to provide automatic IP allocation, subnet mask, and default gateway details.
* 802.1Q trunking was used to allow multiple VLANs to share a single physical link between the router and switches.
* Each VLAN was assigned a unique subnet to prevent conflicts and make management easier.

---

## Testing and Verification

After configuration, connectivity was tested using ping commands between PCs in different VLANs. DHCP functionality was verified by checking if PCs received IP addresses automatically. The setup worked successfully with inter-VLAN communication established and no IP conflicts.

---

## Tools and Technologies Used

Cisco Packet Tracer, Cisco IOS CLI, VLANs, DHCP, Inter-VLAN Routing, and Trunk Links.

---

## Files Included

* project.pkt – Cisco Packet Tracer project file

---

## How to Use

1. Open the file resume1.pkt in Cisco Packet Tracer (version 8 or higher).
2. Turn on all devices and wait for link lights to turn green.
3. Open routers and switches to check configurations.
4. Use ping between PCs in different VLANs to confirm routing.
5. Check that each PC automatically receives IP addresses from the DHCP server.

---

## Learning Outcomes

* Understood VLAN creation and inter-VLAN routing concepts.
* Learned to configure DHCP for automated IP management.
* Gained experience with trunking and router subinterfaces.
* Practiced testing and troubleshooting in a simulated enterprise LAN.

