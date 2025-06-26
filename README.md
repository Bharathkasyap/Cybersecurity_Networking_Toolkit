# Cybersecurity Networking Toolkit

Welcome to the **Cybersecurity Networking Toolkit** – a curated collection of interactive web-based tools designed to simplify networking tasks for cybersecurity analysts and network engineers.

## 🔐 Why This Toolkit?
In cybersecurity operations, analysts frequently rely on subnetting, IP calculations, binary conversions, and firewall planning. These tasks, while routine, are prone to human error when performed manually. This repository automates those steps with visual, interactive tools that:

- Speed up calculations (binary ↔ decimal ↔ IP)
- Help design secure subnet plans
- Simplify documentation for IP ranges and usage
- Assist in incident response (knowing what subnet/IP belongs to what zone)

Whether you're handling alert triage, firewall rule reviews, or setting up segmentation for Zero Trust — this toolkit can help.

---

## 🌐 Tools Included

### 1. Binary to Decimal Converter
Convert any 8-bit binary number into its decimal equivalent using an interactive visual table.

🔗 [Launch Binary to Decimal Converter](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/binary_to_decimal_converter.html)

---

### 2. Subnet Calculator
Plan subnetting intelligently by entering a base network and desired number of hosts. This tool automatically calculates the best-fit subnet for each host group with details like:

🔗 [Launch Subnet Calculator](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/subnet_calculator.html)

### 🔧 Features:
Enter base network IP (e.g., 192.168.0.0)
Enter host requirements (e.g., 60,30,12)

It auto-generates:
- Allocated subnet
- Usable hosts
- Network & Broadcast addresses
- Subnet mask and CIDR prefix

---

### 3. CIDR to Subnet Mask Calculator
Convert CIDR notation (e.g., /26) into its corresponding subnet mask, wildcard mask, and usable host count.

🔗 [Launch CIDR to Subnet Mask Calculator](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/cidr_calculator.html)

---

### 4. IP Address Converter
Convert IPv4 addresses into binary and hexadecimal formats instantly. Helps during packet analysis, firewall rule reviews, and log investigations.

🔗 [Launch IP Address Converter](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/ip_converter.html)

---

### 5. Wildcard Mask Calculator
Quickly convert subnet masks to wildcard masks, useful for writing firewall rules and ACL conditions.

🔗 [Launch Wildcard Mask Calculator](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/wildcard_mask_calculator.html)

---

6. Network ID Calculator
Calculate the network ID based on a given IP address and subnet mask. Useful for access control policies and understanding network boundaries.

🔗 [Launch Network ID Calculator](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/network_id_calculator.html)

---

7. Broadcast Address Calculator
Identify the broadcast address of a subnet using an IP and subnet mask. Essential for understanding communication boundaries within network segments.

🔗 [Launch Broadcast Address Calculator](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/broadcast_address_calculator.html)

---

8. Usable Hosts Calculator
Determine how many IPs are available for actual devices in any given subnet. Helps allocate the right CIDR block to each team or system.

🔗 [Launch Usable Hosts Calculator](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/usable_hosts_calculator.html)

---

9. IP Range Calculator
Calculate the usable IP range, broadcast address, and host span from any CIDR-based network block.

🔗 [Launch IP Range Calculator](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/ip_range_calculator.html)

---

10. Network Class Identifier
Classify any IPv4 address into its class (A–E), view default subnet masks, and understand the network’s typical use case.

🔗 [Launch Network Class Identifier](https://bharathkasyap.github.io/Cybersecurity_Networking_Toolkit/cyber-networking-tools/network_class_identifier.html)

### 🔧 Features:
Input: Any IPv4 address (e.g., 192.168.1.1)

Output:

Network class (A/B/C/D/E)

Default subnet mask

Intended usage (e.g., large networks, multicast)

Helpful for understanding address ranges and class-based planning
---

## 📂 Upcoming Tools
More tools will be added here soon:
- Subnet calculator with CIDR → usable IPs breakdown
- Firewall Rule Planner
- IP Range Documentation Helper
- Zero Trust Visualizer

Stay tuned and feel free to contribute!

---

## 🧠 For Cybersecurity Analysts
If you're a SOC Analyst, Threat Hunter, or working in GRC/Incident Response, these tools will help you:
- Plan detection zones logically
- Document network scopes per team/system
- Avoid subnet overlap in segmentation
- Respond faster by identifying which subnet was hit during incidents

> **Made by analysts, for analysts.**
