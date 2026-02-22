# OSPF-Multi-Router-Lab
OSPFv2 configuration and verification in a 3-router topology using Cisco Packet Tracer.

..............................................................................................................................................
# OSPF Multi-Router Configuration Lab

## Overview
This project demonstrates the configuration and verification of OSPFv2 in a three-router topology using Cisco Packet Tracer.

## Topology
R1 -------- R2 -------- R3

## IP Addressing

R1
- G0/0/0 : 10.1.1.1/30
- Lo0 : 1.1.1.1/24

R2
- G0/0/0 : 10.1.1.2/30
- G0/0/1 : 10.1.1.5/30
- Lo0 : 2.2.2.2/24

R3
- G0/0/0 : 10.1.1.6/30
- Lo0 : 3.3.3.3/24

## OSPF Configuration
- OSPF Process ID: 10
- Area: 0
- Router IDs: 1.1.1.1, 2.2.2.2, 3.3.3.3

## Features Implemented
- OSPF neighbor adjacency
- Router ID configuration
- Passive interfaces
- Route exchange between routers

## Verification Commands
show ip ospf neighbor  
show ip route ospf  
show ip ospf interface brief  

## Result
All routers successfully formed OSPF adjacencies and exchanged routing information.

## Author
Sanaa El habib  – Network Engineer
