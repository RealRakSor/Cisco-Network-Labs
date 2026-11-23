# Cisco Networking Labs

> **🚧 Work in Progress:** This repository is actively being built and documented. Lab topology files (`.pkt`) are uploaded as they are completed, while detailed per-lab write-ups, IP addressing tables, and topology diagrams are being added incrementally.

Hands-on networking and network security labs built in **Cisco Packet Tracer**. This repository documents practical topologies, device configurations, and traffic-flow troubleshooting—moving from foundational Layer 2/Layer 3 switching to segmented enterprise wireless networks and stateful firewall architectures.

## Lab Overview

| # | Lab | Core Technologies & Protocols | Key Focus Areas | Status |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **L2/L3 Packet Tracing & Switching** | OSI Model, ARP, ICMP, MAC Address Tables | Frame/packet encapsulation in Simulation Mode, dynamic vs. static MAC bindings (`show mac-address-table`) | 🚧 Docs in progress |
| **02** | **Enterprise WLAN & VLAN Segmentation** | Cisco 2911, Cisco 2960, WLC-2504, LAP-PT, 802.1Q, DHCP Option 43, CAPWAP | Router-on-a-Stick, VLAN isolation (`MGMT`, `CORP_WIFI`, `GUEST_WIFI`), FlexConnect local switching, P2P client blocking | 🚧 Docs in progress |
| **03** | **Cisco ASA Firewall, DMZ & NAT/PAT** | Cisco ASA 5506-X, Security Levels (`100`/`50`/`0`), Static NAT, Dynamic PAT, ACLs | Perimeter segmentation (`INSIDE`, `DMZ`, `OUTSIDE`), publishing internal web services, stateful traffic inspection (`OUTSIDE_IN` / `INSIDE_IN`) | 🚧 Docs in progress |

## Technical Competencies Demonstrated

* **Switching & Routing:** VLAN segmentation, 802.1Q trunking, Router-on-a-Stick inter-VLAN routing, static routing, and DHCP pool configuration.
* **Enterprise Wireless:** Centralized WLC-2504 management, lightweight AP discovery via DHCP Option 43 (`f104.c0a8.0a0a`), CAPWAP tunnels, FlexConnect, and wireless guest isolation.
* **Perimeter & Firewall Security:** Zone-based security levels on Cisco ASA, network object NAT/PAT translations, DMZ isolation, and ingress/egress Access Control Lists (ACLs).
* **Verification & Troubleshooting:** End-to-end packet inspection in Packet Tracer Simulation Mode, CLI diagnostics, and isolation of misconfigured trunk/ACL/CAPWAP states.

## Repository Structure

```text
Cisco-Networking-Labs/
├── 01-l2-l3-packet-tracing/      # Topology (.pkt) & notes (WIP)
├── 02-enterprise-wlan-wlc/       # Topology (.pkt) & notes (WIP)
├── 03-asa-firewall-dmz/          # Topology (.pkt) & notes (WIP)
└── README.md
