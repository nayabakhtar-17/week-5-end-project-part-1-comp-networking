cosmicode summer internship Week 5 task [END PROJECT PART 1] 

Network Project

Introduction

This file documents the design, implementation, and configuration of a small-to-medium-sized office network. The network includes routers, switches, VLANs, and access points, and is designed to provide secure and reliable connectivity for office devices.here is a detailed report of whole project.

Network Design

The network topology diagram is shown below:
For topology diagram you can go to issues tab 

[Insert network topology diagram]

Implementation

The network was implemented using the following devices:

- Routers: Cisco ISR 4321
- Switches: Cisco Catalyst 2960X
- Access Points: Cisco Aironet 2700
- VLANs: 2 VLANs (Admin, Employee)

Configuration

The network was configured using the following settings:

- IP Addressing: 192.168.10.0/24 (Admin), 192.168.20.0/24 (Employee)
- NAT: Enabled on router for internet access
- DHCP: Enabled on router for dynamic IP assignment
- VLANs: Configured on switches and access points

Testing and Troubleshooting

The network was tested for connectivity and communication between devices. The following issues were encountered and resolved:

- Issue 1: Devices not receiving IP addresses
    - Solution: Checked DHCP configuration and ensured that DHCP was enabled
- Issue 2: Devices not able to access internet
    - Solution: Checked NAT configuration and ensured that NAT was enabled

Network Security

The following network security features were implemented:

- Firewall rules: Configured to allow only necessary traffic
- ACLs: Configured to restrict access to sensitive areas of the network
- VPNs: Configured for secure remote access

Network Monitoring and Performance

The following network monitoring and performance tools were configured:

- SNMP: Configured for network monitoring
- Syslog: Configured for log collection
- Performance analysis tools: Configured to monitor network performance

Summary of project

This network project involved the design, implementation, and configuration of a small-to-medium-sized office network. The network was designed to provide secure and reliable connectivity for office devices, and was implemented using Cisco devices. The network was tested and troubleshooted, and network security features were implemented to ensure the security of the network. Finally, network monitoring and performance tools were configured to ensure the network is running optimally.

Author[Nayab]

Version [1.0]


