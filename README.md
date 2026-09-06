# Enterprise Multi-Layer Network — CCNA Project

CCNA Enterprise network project using Cisco Packet Tracer, spanning 3 floors with approximately 130 end devices, featuring:

* **Hierarchical architecture** (Core, Distribution, Access)
* **VLAN segmentation** (Data, Voice, Management, Guest/Employee Wi-Fi) with Inter-VLAN routing
* **High Availability** using HSRP (Virtual Gateways)
* **OSPF dynamic routing** across Core and Distribution layers
* **Enterprise VoIP telephony** using Cisco CME and DHCP Option 150
* **Centralized Wireless networking** using a Cisco 3500 Series WLC
* **STP** configured to prevent Layer 2 loops
* **Device Security & Access:** Port Security, PortFast, and SSH
* **DHCP** for automatic IP assignment across all departments
* **PAT (NAT Overload) and ACLs** for secure external ISP routing

## 🛠️ How to Test the Network
1. Open the `.pkt` file using Cisco Packet Tracer.
2. Ping from **PC1 (VLAN 40)** to the **External ISP Router (200.1.1.2)** to verify NAT/PAT.
3. Check the **IP Phone** display to ensure it received an extension from the CME.
4. Open the WLC interface via web browser at `192.168.100.2` to view wireless configurations.
