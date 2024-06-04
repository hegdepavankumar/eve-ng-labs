# 🌐 EVE-NG Labs Catalog

Welcome to the **EVE-NG Labs Catalog**! This repository is a comprehensive collection of network simulation labs designed for network engineers, students, and professionals who want to enhance their skills in routing, switching, and firewall technologies. These labs utilize EVE-NG (Emulated Virtual Environment - Next Generation) to provide a hands-on, practical learning experience.

## 🔧 Lab Categories

### 1. Routing and Switching Simulation 🛤️🖧
- **Description:** Dive into dynamic and static routing. This section includes labs on OSPF, EIGRP, BGP, and more.
- **Devices:** Cisco Routers & Switches (various models)

### 2. Firewall Simulation 🔥
- **Description:** Learn to secure networks with industry-leading firewall technologies. This section includes labs on:
  - **Cisco ASA & Firepower** 🛡️
  - **Palo Alto** 🔐
  - **Checkpoint** 🔲
  - **FortiGate** 🏰

## 📁 Downloadable Files

Each lab comes with:
- **Topology Files:** Topology files for EVE-NG. (Compatible with both Community and PRO)✅
- **Configuration Files:** Initial and final configuration files. ❌
- **Problem Statements:** Detailed problem statements to guide you through each lab.✅

## 🚀 Getting Started

To get started, follow these steps:

1. **Import Labs into EVE-NG:**
   - Follow the instructions in the README file in each lab directory to import and set up the labs in your EVE-NG environment.
   - Steps to Follow : ![check now]()

## 📚 Learning Objectives

By working through these labs, you will:
- Gain hands-on experience with routing and switching protocols.
- Understand the configuration and management of various firewalls.
- Develop troubleshooting skills in a simulated network environment.
- Exploring Multiple real-time Problem statement.

<br>

<hr>


<p align="center">
  <img src="https://github.com/hegdepavankumar/eve-ng-labs/assets/85627085/55c46abb-c0ef-4fcc-8cdf-84cbd2885879" alt="Let's Get Started">
</p>

<br>

<br>
<br>

 
# Lab 1: IPv4 and IPv6 Addressing

![IPv4 and IPv6 Addressing](https://github.com/hegdepavankumar/eve-ng-labs/assets/85627085/3a5f0015-c68b-4018-abbc-063efd3d2a97)   


## 📝 Problem Statement
Objective: Configure IPv4 and IPv6 Addresses on Cisco Routers

- You are tasked with configuring both IPv4 and IPv6 addresses on a Cisco router.
- The router has two interfaces: GigabitEthernet 0/0 and GigabitEthernet 0/1.
- The IPv4 address for GigabitEthernet 0/0 should be 192.168.1.1/24 and for GigabitEthernet 0/1 should be 192.168.2.1/24.
- The IPv6 address for GigabitEthernet 0/0 should be 2001:192:168:1::1/64 and for GigabitEthernet 0/1 should be 2001:192:168:2::1/64

## 📁Download Topology :   [Click Here](https://github.com/user-attachments/files/15542449/IPv4.and.IPv6.Addressing.zip)  🔫

<br>


<br>


# Lab 2: Inter VLAN Routing with Multilayer Switch

![Untitled](https://github.com/hegdepavankumar/eve-ng-labs/assets/85627085/715ccd5e-996a-412e-9d35-b33e380d43a6)


## 📝 Problem Statement

Objective: Cisco network setup consisting of both Layer 2 and Layer 3 switches

- Assign an IP address to the Layer 3 switch.
- Enable routing on the Layer 3 switch.
- Create VLANs and assign them to specific ports on both Layer 2 and Layer 3 switches.

Requirements:

- Assign IP Address to Layer 3 Switch:
- Choose an appropriate IP address and subnet mask for the management interface of the Layer 3 switch.
-  Enable Routing on Layer 3 Switch:
- Enable IP routing to allow the Layer 3 switch to route traffic between different VLANs.

Create VLANs:
- Define multiple VLANs (e.g., VLAN 10 for the Sales department, VLAN 20 for the HR department).
- Assign these VLANs to specific ports on both Layer 2 and Layer 3 switches.
-  Ensure inter-VLAN routing is configured to allow communication between VLANs on the Layer 3 switch.

## 📁Download Topology :    [Click Here](https://github.com/user-attachments/files/15542609/Inter.VLAN.Routing.with.Multilayer.Switch.zip) 🔫


<br>


<br>


# Lab 3: Two-tier-architecture

![Two-tier-architecture](https://github.com/hegdepavankumar/eve-ng-labs/assets/85627085/95056c2a-76b8-4c41-aca3-4ebce10465a9)


## 📝 Problem Statement: Understanding a Simple 2-Tier Network Architecture

 Objective:

Design and understand a basic 2-tier network topology. This topology will include end devices (such as computers or workstations) connected to a switch, which in turn connects to a router providing access to external networks like the internet. This exercise aims to help you grasp the fundamental components and functions of a simple network architecture.

 Components:

1. End Devices:
    - 4 Computers (PC1, PC2, PC3, PC4)

2. Network Devices:
    - 1 Switch (Switch1)
    - 1 Router (Router1)

3. Network Connections:
    - Ethernet cables to connect PCs to the switch
    - An Ethernet cable to connect the switch to the router

Network Requirements:

1. IP Addressing:
    - Use a private IP address range (e.g., 192.168.1.0/24).
    - Assign static IP addresses to each PC.
    - Configure the router with an appropriate IP address within the same subnet.

2. Switch Configuration:
    - Basic configuration to ensure all ports are active and correctly connected.

3. Router Configuration:
    - Configure the router with an IP address within the network subnet.
    - Set up the router to provide internet access or simulate an external network connection.

Steps to Complete the Task:

1. Design the Topology:
    - Draw a simple diagram with 4 PCs connected to Switch1.
    - Show a connection from Switch1 to Router1.

2. Assign IP Addresses:
    - Assign IP addresses to each PC. Example:
        - PC1: 192.168.1.2
        - PC2: 192.168.1.3
        - PC3: 192.168.1.4
        - PC4: 192.168.1.5
    - Assign the switch a management IP if needed (e.g., 192.168.1.1).

3. Connect Devices:
    - Physically or virtually (in a network simulator) connect PCs to the switch using Ethernet cables.
    - Connect the switch to the router using an Ethernet cable.

4. Configure the Router:
    - Set the router’s internal IP address to 192.168.1.1.
    - Configure the router to route traffic to an external network (e.g., simulate internet access).

5. Verify Connectivity:
    - Ping from one PC to another to ensure local network connectivity.
    - Ping the router from each PC to verify they can reach the gateway.
    - If an external network is configured, ping an external IP address to ensure internet connectivity.

 Expected Outcomes:

1. Local Connectivity:
    - All PCs should be able to communicate with each other.
    - PCs should be able to reach the router.

2. External Connectivity:
    - If configured correctly, PCs should be able to reach an external network (e.g., ping 8.8.8.8 for internet).

Deliverables:

1. Network Diagram:
    - A visual representation of the 2-tier network topology.

2. IP Address Plan:
    - A table listing each device and its assigned IP address.

3. Configuration Files:
    - Any configuration settings applied to the router and switch.

4. Connectivity Test Results:
    - Ping test results showing successful connectivity between devices.

## 📁Download Topology :    [Click Here](https://github.com/user-attachments/files/15542759/Two-tier-architecture.zip)   🔫





<br>

<hr>

## 💬 Contributing

We welcome contributions! If you have a lab you’d like to add or improvements to suggest, please submit a pull request.

## 🛠️ Issues

If you encounter any issues, please open an issue in this repository. We will address it as soon as possible.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```

Make sure to replace `https://github.com/yourusername/eve-ng-labs-catalog.git` with the actual URL of your repository and update the paths to your screenshots accordingly. This will make your repository more attractive and user-friendly on GitHub.
