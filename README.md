# Cisco-Packet-Tracer-VLSM-Design
A Cisco Packet Tracer project implementing Variable Length Subnet Masking (VLSM) to optimize IP address allocation for a multi-departmental enterprise network.


## 📌 Project Overview
This project demonstrates the efficient allocation of IP addresses for a multi-departmental network using VLSM. The goal was to minimize address wastage by tailoring subnet masks to the specific host requirements of each LAN.

## 🛠️ Skills Demonstrated
* **VLSM Calculation:** Determined subnet sizes based on host requirements (Largest to Smallest).
* **Network Topology:** Designed a hierarchical network with Routers, Switches, and End Devices.
* **Cisco IOS Configuration:** Configured interfaces, IP addresses, and default gateways via CLI.
* **Connectivity Testing:** Verified end-to-end communication using Ping and Traceroute.

## 🗺️ Network Topology
![Network Topology](Topologyjpg)

## 📊 Addressing Scheme
| Subnet Name | Hosts Needed | Network Address | Subnet Mask | Gateway |
| :--- | :--- | :--- | :--- | :--- |
| LAN A (Sales) | 60 | 192.168.1.0/26 | 255.255.255.192 | 192.168.1.1 |
| LAN B (HR) | 20 | 192.168.1.64/27 | 255.255.255.224 | 192.168.1.65 |
| WAN (Links) | 2 | 192.168.1.96/30 | 255.255.255.252 | N/A |



## 🚀 How to Use
1. Download the `Assignment for VLSM.pkt` file.
2. Open it using **Cisco Packet Tracer (v8.0 or higher)**.
3. Test connectivity by pinging from PC-A to PC-B.
