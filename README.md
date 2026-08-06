# Cisco Packet Tracer Networking Labs

This repository documents my practical networking labs completed using Cisco Packet Tracer.

## About This Repository

I am building foundational skills in computer networking as part of my transition from telecommunications into IT infrastructure, networking, cloud and cybersecurity.

The labs in this repository will cover:

* IP addressing
* Subnet masks
* PC-to-PC connectivity
* Switch configuration
* Router configuration
* Ping testing
* Network troubleshooting

## Lab 1: Basic PC-to-PC Connectivity

### Objective

To connect two computers in Cisco Packet Tracer, assign IP addresses and test communication using the ping command.

### Devices Used

* 2 PCs
* 1 Copper Cross-Over cable

### IP Configuration

| Device | IP Address   | Subnet Mask   |
| ------ | ------------ | ------------- |
| PC0    | 192.168.2.10 | 255.255.255.0 |
| PC1    | 192.168.2.20 | 255.255.255.0 |

### Test Command

From PC0, open Command Prompt and run:

```bash
ping 192.168.2.20
```

### Expected Result

The ping should return successful replies when both PCs:

* Are connected correctly
* Have valid IP addresses
* Use the same subnet mask
* Are in the same network

### What I Learned

* How to connect two computers in Cisco Packet Tracer
* How to assign static IP addresses
* How subnet masks identify the network
* How to test connectivity using ping
* How incorrect settings can cause a request timed out message

## Tools

* Cisco Packet Tracer
* Windows Command Prompt

## Future Labs

* Connecting PCs through a switch
* Configuring a router
* Connecting two separate networks
* Troubleshooting IP and subnet errors
## Lab Screenshot

![Lab 1 PC Connectivity](lab1-pc-connectivity.png)
