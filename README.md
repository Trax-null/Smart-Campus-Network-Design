Project Overview

This project demonstrates the design and implementation of a structured campus network architecture using Local Area Networks (LANs), Virtual Local Area Networks (VLANs), multilayer switching, dynamic routing, and network redundancy mechanisms.

The architecture is designed to support departmental segmentation, efficient inter-VLAN communication, and improved network availability.

Technologies and Protocols

Cisco Packet Tracer 9.0

VLAN and Inter-VLAN Routing

Layer 2 and Layer 3 Switching

HSRP (Hot Standby Router Protocol)

OSPF (Open Shortest Path First)

STP (Spanning Tree Protocol)

LACP EtherChannel

ASA Firewall Placement

Wired and Wireless Network Infrastructure

Network Architecture

The proposed topology incorporates:

Dual multilayer core switches

Department-based VLAN segmentation

Redundant gateway configuration using HSRP

OSPF adjacency between core switches

Link aggregation using LACP EtherChannel

Spanning Tree Protocol for Layer 2 loop prevention

Wired and wireless departmental connectivity

Firewall placement at the network perimeter

VLAN Segmentation

The project uses the following VLAN identifiers:

VLAN ID

Allocation

10

Departmental network

20

Departmental network

30

Departmental network

40

Departmental network

60

Departmental network

90

Departmental network

Refer to the project documentation for the complete departmental mapping and configuration details.

Key Implementations

Designed a hierarchical campus network topology.

Configured VLAN-based network segmentation.

Implemented inter-VLAN routing.

Configured HSRP for gateway redundancy.

Established OSPF adjacency between core switches.

Implemented LACP EtherChannel for link aggregation.

Applied STP for Layer 2 loop prevention.

Integrated wired and wireless network segments.

Verification

The project documentation and simulation demonstrate configuration and verification of selected networking components, including:

VLAN configuration

HSRP configuration

OSPF neighbor adjacency

EtherChannel configuration

Network topology and connectivity

Project Limitations and Future Scope

The following enhancements are identified as future work and should not be interpreted as fully implemented or validated:

NAT/PAT configuration and end-to-end Internet connectivity testing

Guest VLAN isolation using ACLs

Centralized server infrastructure

DHCP centralization

Network monitoring and logging

IPv6 implementation
Tools

Cisco Packet Tracer

Networking CLI

Microsoft PowerPoint

Microsoft Word

Contributors

This is a collaborative academic project developed by:

Ishani Saha

Vikas Kumar

Kiran Kour

Shibabrata Saha

Aryan Sharma

Project Classification

Academic Networking Project | Network Design | Network Simulation | Cisco Packet Tracer

Disclaimer

This project was developed for academic and educational purposes. The simulated architecture does not represent a fully deployed production campus network. Refer to the documented implementation status and limitations before using it as a deployment reference.

Quantitative failover and redundancy testing

Real hardware deployment and validation
