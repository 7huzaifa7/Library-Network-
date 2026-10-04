# 📚 Multi-Floor Library Network – Cisco Packet Tracer

A multi-floor library network designed and configured in Cisco Packet Tracer to develop my practical networking skills.

The network is spread across three floors with multiple departments, each separated using VLANs and their own IPv4 subnets. The project also includes dynamic routing and several basic network security features.

## 🌐 Network Overview

The network contains three floors with the following departments:

### Floor 1
- Logistics
- Store
- Reception

### Floor 2
- Sales
- HR
- Finance

### Floor 3
- IT
- Admin

Each department operates on its own VLAN and subnet to provide network segmentation.

## ⚙️ Features

- VLAN configuration and network segmentation
- IPv4 addressing and subnetting
- DHCP for automatic IP address assignment
- Inter-VLAN routing
- 802.1Q trunking
- OSPF dynamic routing between routers
- SSH remote access
- Access Control Lists (ACLs)
- Switch port security
- Wireless connectivity
- Cross-VLAN and cross-floor connectivity testing

## 🔐 Network Security

Several security features were implemented within the network.

**SSH** was configured to provide secure remote access to network devices.

**Port Security** was configured on switch ports to restrict the devices that can connect to the network.

**ACLs** were used to control communication between different parts of the network.

## 🔧 Testing & Troubleshooting

An important part of this project was testing and troubleshooting the network after configuration.

During the project, I encountered and resolved issues involving:

- DHCP address assignment
- VLAN configuration
- Trunk ports
- OSPF connectivity
- Port security

Connectivity was tested using tools such as `ping`, `ipconfig`, `show ip route`, and `show ip ospf neighbor`.

This helped me better understand how different networking technologies work together rather than only learning the concepts theoretically.

## 🛠️ Technologies & Concepts

`Cisco Packet Tracer` `VLANs` `DHCP` `OSPF` `SSH` `ACLs` `Port Security` `Inter-VLAN Routing` `802.1Q` `IPv4`

## 📸 Network Topology

![Network Topology](network-topology.png)

## 📁 Project File

The Cisco Packet Tracer `.pkt` file is included in this repository and can be opened using Cisco Packet Tracer.

## 🎯 What I Learned

This project gave me practical experience designing, configuring, testing and troubleshooting a multi-network environment.

I particularly enjoyed troubleshooting connectivity issues and seeing devices successfully communicate between different VLANs and floors.
