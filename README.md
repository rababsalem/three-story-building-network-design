
# Three-Story Building Network Design (تصميم مبنى شبكات مكون من 3 طوابق)

A complete network design and simulation for a **three-story building** implemented in **Cisco Packet Tracer**. The architecture covers departmental segmentation, Layer 2/Layer 3 switching, dynamic routing, centralized network services, wireless access, security controls, and outbound NAT translation.

## Configuration Steps
1. **Basic Settings & SSH:** Configure foundational device settings along with SSH access on routers and Layer 3 switches.
2. **VLANs & Port Roles:** Assign VLANs and configure access and trunk ports across Layer 2 and Layer 3 switches.
3. **Switchport Security:** Apply port security policies to protect the finance department ports.
4. **Subnetting & IP Addressing:** Plan subnets and assign IP addresses across departments and network segments (including `172.16.1.0/25` – `172.16.3.128/28`).
5. **Dynamic Routing (OSPF):** Configure OSPF routing across routers and Layer 3 switches for end-to-end reachability.
6. **Server Room Addressing:** Assign static IP addresses to devices inside the server room (`172.16.3.128/28`).
7. **DHCP Server Configuration:** Set up and configure the centralized DHCP server for automated IP distribution.
8. **Inter-VLAN Routing & DHCP Relay:** Enable inter-VLAN routing on Layer 3 switches and configure `ip helper-address` to forward DHCP requests.
9. **Wireless Network:** Configure wireless access points and client connectivity across departments.
10. **PAT & Access Control List (ACL):** Implement PAT (NAT Overload) on serial WAN interfaces (`Serial0/0/0`, `Serial0/0/1`) paired with ACL filtering.
11. **Verification & Testing:** Validate connectivity, routing tables, DHCP leases, NAT translations, and remote access.

## Repository Contents
- `/topology` – Cisco Packet Tracer (`.pkt`) project file.
- `/configs` – Router and switch configuration scripts.
- `/screenshots` – High-resolution views of the three-story building topology and floor/department segments.
```[cite: 2]
