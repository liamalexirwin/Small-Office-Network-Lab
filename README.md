# Small Office Network Lab

## Overview
Built a small office local area network (LAN) in Cisco Packet Tracer 
connecting 4 PCs through a managed switch. Practiced manual IP addressing, 
cable selection, and verified connectivity through ping testing.

## Network Topology
![Network Topology](screenshots/topology.png)

## Objectives
- Connect 4 PCs to a switch in a LAN environment
- Manually assign static IP addresses to each device
- Verify full connectivity between all devices using ping
- Understand cable types and when each is appropriate

## Environment
| Component | Details |
|---|---|
| Software | Cisco Packet Tracer |
| Devices | 1 x 2960 Switch, 4 x PCs |
| Cable Type | Copper Straight-Through |
| Network | 192.168.1.0/24 |

## IP Address Table
| Device | IP Address | Subnet Mask |
|---|---|---|
| PC1 | 192.168.1.1 | 255.255.255.0 |
| PC2 | 192.168.1.2 | 255.255.255.0 |
| PC3 | 192.168.1.3 | 255.255.255.0 |
| PC4 | 192.168.1.4 | 255.255.255.0 |

## Steps Taken
1. Added a 2960 switch and 4 PCs to the Packet Tracer canvas
2. Connected each PC to the switch using copper straight-through cables
3. Assigned static IP addresses and subnet masks to each PC
4. Opened Command Prompt on each PC and ran ping tests to verify connectivity
5. Checked the switch MAC address table using `show mac address-table`

## Commands Used
