# CCNA Project 01 - Small Office Network

## Project Overview

Designed and implemented a small office network using Cisco Packet Tracer.

## Technologies Used

* Cisco Packet Tracer
* VLAN
* Router-on-a-Stick
* DHCP
* Inter-VLAN Routing
* Trunking

## Network Topology

* 1 Router (Cisco 2911)
* 1 Switch (Cisco 2960)
* 3 VLANs

  * VLAN 10 (Admin)
  * VLAN 20 (Accounting)
  * VLAN 30 (Office)

## IP Addressing

| VLAN    | Network        | Gateway     |
| ------- | -------------- | ----------- |
| VLAN 10 | 192.168.1.0/24 | 192.168.1.1 |
| VLAN 20 | 192.168.2.0/24 | 192.168.2.1 |
| VLAN 30 | 192.168.3.0/24 | 192.168.3.1 |

## Features Implemented

* VLAN Segmentation
* DHCP Configuration
* Router-on-a-Stick
* Trunk Port Configuration
* Inter-VLAN Communication

## Verification

* DHCP leases successfully assigned
* End devices received correct IP addresses
* Successful connectivity tests between VLANs

## Skills Demonstrated

CCNA, Switching, Routing, DHCP, VLANs, Network Troubleshooting, Cisco IOS
