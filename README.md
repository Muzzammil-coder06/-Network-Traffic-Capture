# Task 5: Network Traffic Capture and Protocol Analysis


## 🌟 Objective
To capture live network packets using Wireshark and identify basic protocols and traffic types.

## 🔧 Tools
- Wireshark (open-source packet analyzer)

## 📂 Protocols Identified

### 1. DNS (Domain Name System)
- **Purpose**: Resolves human-readable domain names to IP addresses.
- **Captured Activity**: `google.com` was resolved to `142.250.182.14`
- **Filter Used**: `dns`

### 2. HTTP (Hypertext Transfer Protocol)
- **Purpose**: Used for unencrypted web communication.
- **Captured Activity**: HTTP GET request to `example.com`
- **Filter Used**: `http`

### 3. TCP (Transmission Control Protocol)
- **Purpose**: Ensures reliable transmission of data packets.
- **Captured Activity**: TCP handshake and session packets during browsing.
- **Filter Used**: `tcp`

## 📁 Files Included
- `network_capture.pcap` — Raw packet capture file (to be exported from Wireshark)
- `README.md` — Task explanation and summary of findings

## 📸 Screenshots
Include relevant screenshots of:
- The capture in progress
- Filters applied (e.g., DNS, HTTP, TCP)
- Details of a selected packet (with protocol info)

## 🔗 How to View the Capture File
1. Open Wireshark.
2. File > Open > Select `network_capture.pcap`
3. Apply filters such as `http`, `dns`, `tcp` to analyze specific traffic.

## 🚀 Outcome
Hands-on experience in:
- Capturing live packets
- Filtering network traffic
- Identifying and analyzing protocols
