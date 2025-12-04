# Network Design and Connectivity Project
Network design, configuration, and connectivity testing for coursework 6G5Z0020 (London–Manchester topology).

This repository contains the Packet Tracer files, configuration samples, diagrams, and supporting materials for a two-branch enterprise network designed using Cisco Packet Tracer. The network connects London and Manchester offices through a routed WAN link and includes full LAN segmentation, static routing, VLAN configuration, and end-to-end connectivity testing.

# Project Overview

The project implements a structured network across two remote sites. Each site includes routers, switches, and PCs organised into logical subnets and VLANs. A point-to-point WAN connection enables communication between the branches. The design uses:
- Static IP addressing
- VLAN segmentation
- Static routing and RIP v2 (where applied)
- Gateway configuration and interface management
All configurations were manually implemented and verified using Cisco IOS commands and Packet Tracer’s simulation tools.

# Connectivity Testing

Connectivity was validated through:
- Router-to-router ping over the WAN
- Router-to-PC tests within each LAN
- End-to-end communication between PCs in London and Manchester
- Routing table inspection using show ip route
All tests completed successfully, confirming correct addressing, routing, and VLAN configuration.

# Academic Note

The full report is submitted separately through Moodle in accordance with university requirements. This repository is for demonstration and portfolio support only.


