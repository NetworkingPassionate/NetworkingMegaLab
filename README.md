# NetworkingMegaLab
<img width="997" height="571" alt="image" src="https://github.com/user-attachments/assets/8100b9b6-ba3d-46f5-83f8-ee9475bd5b9e" />

<img width="1126" height="633" alt="image" src="https://github.com/user-attachments/assets/78230fb8-bc3c-412d-b488-ada5c57e728d" />


# 🛠️ CCNA Mega Lab – Jeremy’s IT Lab Inspired Network Simulation

This project is a comprehensive CCNA 200-301 practice lab inspired by Jeremy’s IT Lab’s end-of-course “Mega Lab” challenge. It was designed and implemented to demonstrate full-stack network engineering skills across Layer 2 and Layer 3 domains within a simulated Cisco environment using [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).

## 📦 Lab Overview

This multi-device topology simulates a realistic enterprise deployment and showcases:

- Multi-area **OSPFv2 routing**
- Segmented **VLAN architecture** with trunking and inter-VLAN routing
- Dynamic IP assignment using **DHCP**
- **Spanning Tree Protocol (STP)** configuration and priority tuning
- **Port security** enforcement with MAC address constraints
- Basic **Access Control Lists (ACLs)** for traffic filtering
- **Wireless LAN** setup with SSID authentication
- DNS and NAT functionality (where applicable)
- End-to-end connectivity validation and debugging

## 🌐 Topology Summary

- **Core & Distribution Layer**: 3 routers and 3 switches forming the backbone with OSPF adjacency
- **Access Layer**: VLAN-tagged endpoints across multiple switches
- **Wireless Network**: WLC and AP configured for secure WLAN access
- **Clients**: PCs across VLANs with DHCP leases, DNS resolution, and ACL-controlled communication

## 🧠 Protocol Highlights

| Protocol | Purpose | Configuration Role |
|---------|--------|-------------------|
| OSPF    | Dynamic routing | Inter-router connectivity and redundancy |
| VLANs   | Network segmentation | Isolating traffic and enabling security policies |
| DHCP    | IP assignment | Automating client network configuration |
| STP     | Loop prevention | Ensuring optimal Layer 2 paths |
| ACLs    | Traffic control | Restricting inter-VLAN access |
| Port Security | Physical security | Limiting access to trusted MACs |
| WLAN    | Wireless access | Secure SSID broadcast and authentication |

## 🧪 Validation & Testing

- Verified full network convergence using `ping`, `tracert`, and OSPF adjacency checks (`show ip ospf neighbor`)
- VLAN integrity confirmed via `show vlan brief` and endpoint connectivity
- DHCP bindings and leases validated (`show ip dhcp binding`)
- ACL functionality tested with inter-VLAN communication scenarios
- Port security alerts generated on MAC violations
- Wireless authentication confirmed through mobile client association

## 📁 Included Files

- `MegaLab.pkt` – Cisco Packet Tracer project file
- `README.md` – You’re looking at it 🙂


