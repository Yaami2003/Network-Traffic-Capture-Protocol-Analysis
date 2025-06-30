# Network-Traffic-Capture-Protocol-Analysis
## 🎯 Objective
To capture live network traffic using Wireshark and identify at least 3 different network protocols.

## 🛠 Tools Used
- Wireshark
- Command Prompt (`ping`)
- Chrome Browser

## 📡 Protocols Identified

### 1. TCP (Transmission Control Protocol)
- Captured using the filter `tcp`
- Shows traffic over port 443 (used in HTTPS)

### 2. TLSv1.2 (Transport Layer Security)
- Encrypted web traffic
- Captured on top of TCP packets (HTTPS sessions)

### 3. ICMP (Internet Control Message Protocol)
- Captured using the `ping` command
- Example: Destination unreachable messages shown in Wireshark

## 🔍 HTTP Not Captured?
Most modern websites auto-redirect to **HTTPS**, so plain `http` is rare.
Captured traffic appears as **TLSv1.2**, which is secure HTTP.

## 📷 Screenshots
- `tcp_filter.jpg`
- `icmp_ping.jpg`
  

## 📁 Files Included
- `network_traffic.pcap`
- `README.md`
- Screenshot files

---
