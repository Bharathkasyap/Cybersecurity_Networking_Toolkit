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
