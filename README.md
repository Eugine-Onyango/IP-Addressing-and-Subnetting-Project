# IP-Addressing-and-Subnetting-Project
This project helps to understand IP addressing and subnetting concepts. I will design subnet schemes, assign IP ranges, and verify network communication across different subnets.


Status:Complete✅

Project Overview
I designed and configured a segmented network to understand VLSM (Variable Length Subnet Masking) and Routing concepts. Instead of a flat network, I "sliced" the network `192.168.10.0/24` into distinct subnets to manage traffic flow efficiently.

The Topology
I treated the network like a segmented event space:
The Host (Router):Managing traffic between zones.
The Subnets:
    HR:192.168.10.0/26
    Sales:192.168.10.64/26
    IT):192.168.10.128/26

Technical Skills Demonstrated
Subnetting: Calculated /26 masks (255.255.255.192) to create 4 subnets from one block.
Router on a Stick:Configured Gigabit interfaces as Gateways (`.1`, `.65`, `.129`).
Verification:Confirmed routing via ICMP Pings.
    Local Ping:TTL=128 (Direct)
    Routed Ping:TTL=127 (Validated Router Hop)

Tools Used
Cisco Packet Tracer
Cisco IOS Command Line
