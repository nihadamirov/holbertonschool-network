
# Networking Basics #0

This repository contains the basic networking project from Holberton School. The purpose of this project is to introduce and explore fundamental concepts in networking, including the OSI model, types of networks (LAN, WAN, Internet), IP addresses, TCP/UDP protocols, and more.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Concepts](#key-concepts)
- [Requirements](#requirements)
- [Tasks](#tasks)
- [How to Run](#how-to-run)
- [Resources](#resources)

## Project Overview
This project covers the foundational concepts of networking and aims to make you proficient in understanding how networks function, how devices communicate, and how different protocols operate. By the end of this project, you should be able to explain the key concepts of networking to anyone and be comfortable using networking tools like `ping`, `netstat`, and basic shell scripting to interact with network devices.

## Key Concepts
- **OSI Model**: Understand the seven-layer OSI (Open Systems Interconnection) model and how data is transferred from one computer to another through different layers.
- **LAN/WAN**: Learn the differences between Local Area Networks (LAN) and Wide Area Networks (WAN), their typical uses, and geographic sizes.
- **IP Address**: Grasp what an IP address is and the difference between private and public IP addresses, as well as IPv4 and IPv6.
- **TCP/UDP**: Explore the most common transport protocols used on the Internet and understand the differences between TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).
- **Ports**: Get familiar with commonly used network ports such as 22 (SSH), 80 (HTTP), and 443 (HTTPS).
- **ICMP/Ping**: Use the `ping` command to check the connectivity of a device within a network.

## Requirements
- All Bash script files are developed and tested in **Ubuntu 20.04 LTS**.
- Scripts must follow the format:
  1. The first line should be `#!/usr/bin/env bash`.
  2. The second line should contain a comment explaining the script's purpose.
- Ensure that your scripts are executable and pass `shellcheck` without errors.

## Tasks
1. **OSI Model**: Answer conceptual questions related to the OSI model.
2. **Types of Network**: Define the types of networks (LAN, WAN, Internet) and their use cases.
3. **MAC and IP Address**: Distinguish between MAC and IP addresses, and explain their roles in a network.
4. **UDP and TCP**: Understand and compare the key characteristics of the TCP and UDP protocols.
5. **TCP and UDP Ports**: Write a script to display active TCP/UDP ports and their associated processes.
6. **Is the Host on the Network**: Write a script that uses `ping` to check if an IP address is reachable.

## How to Run
To execute any of the Bash scripts in this repository, follow these steps:
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/holbertonschool-network.git
   ```
2. Navigate to the project directory:
   ```bash
   cd holbertonschool-network/basics_0
   ```
3. Make sure the Bash script you want to run is executable:
   ```bash
   chmod +x <script_name>.sh
   ```
4. Run the script using the command:
   ```bash
   ./<script_name>.sh
   ```

## Resources
- [OSI Model](https://www.geeksforgeeks.org/layers-of-osi-model/)
- [Types of Networks](https://www.techtarget.com/searchnetworking/definition/LAN)
- [TCP vs UDP](https://www.geeksforgeeks.org/difference-between-tcp-and-udp/)
- [MAC Address](https://www.webopedia.com/definitions/mac-address/)
- [IP Address](https://www.lifewire.com/what-is-an-ip-address-2625920)

