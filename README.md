# Hybrid-Azure-Vpn-Project
Hybrid Cloud Site-to-Site VPN (On-Prem VMware → Microsoft Azure)

Overview
This project demonstrates the design and implementation of a hybrid cloud networking environment connecting an on-premises VMware lab to Microsoft Azure using a Site-to-Site IPsec VPN. The objective was to simulate a realistic enterprise hybrid architecture with secure communication between local infrastructure and cloud workloads using private IP connectivity.

The environment was built using Microsoft Azure networking services and a Linux-based VPN gateway running strongSwan within a VMware Workstation lab. The project focused on:
Hybrid cloud networking | Secure IPsec tunnel configuration | Azure Virtual Network architecture | Routing and traffic flow validation | Firewall and NAT configuration | VPN troubleshooting and diagnostics

Although the final tunnel establishment was limited by lack of administrative access to the upstream home router for IPsec passthrough/UDP forwarding, all core infrastructure, routing, VPN negotiation, and security configurations were successfully implemented and validated.
