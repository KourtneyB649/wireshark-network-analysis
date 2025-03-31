# wireshark-network-analysis
Capturing and analyzing network packets using Wireshark
# Wireshark Network Analysis

## Overview
This project demonstrates packet capturing and basic network traffic analysis using **Wireshark**. Traffic was captured over a live network using the `en0` (Wi-Fi) interface on macOS. The goal is to explore how protocols interact in real time and build foundational experience in packet analysis.

## Objective
- Capture live traffic using Wireshark
- Analyze network activity (UDP, TLS, ICMPv6, mDNS, etc.)
- Identify packet structure, IP flow, and protocol behavior
- Document findings and build a hands-on InfoSec portfolio

## Tools Used
- macOS Terminal
- Wireshark v4.4.5
- ChmodBPF (to enable packet capture)
- GitHub

## Key Accomplishments
- **Packet Capture:** Successfully captured real-time traffic using Wireshark on Mac.
- **Protocol Insight:** Identified various protocols including TLSv1.2, UDP, ICMPv6, and mDNS.
- **Hex Analysis:** Observed packet structure at the byte level to understand how data travels.
- **Documentation:** Uploaded `.pcapng` file and findings to GitHub for public portfolio use.

## File
- `wireshark_analysis.pcapng`: Packet capture showing traffic across multiple protocols.

## GitHub
[github.com/KourtneyB649/wireshark-network-analysis](https://github.com/KourtneyB649/wireshark-network-analysis)
