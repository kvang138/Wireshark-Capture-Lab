# 🦈🕸️📶Wireshark Network Packet Capture and Protocol Analysis Lab
Lab for using Wireshark to capture and analyze network packets and protocols.


## 📝Overview
In this project, I used Wireshark to capture and analyze network packets and protocols.
  ### 🛜📦 Traffic Types/Protocols Captured
  - ICMPv6 — Captured via `ping google.com`. 
  - DNS — Captured via `nslookup openai.com` over IPv6.
  - TCP Three-Way Handshake — Captured via a local connection with the router.
  - HTTP — Captured via a local web server on the local computer.
  - Captured ARP packets on the local network.


## 📸Screenshots

### 1. Capturing Echo (Ping) requests and replies to and from google.com via ICMPv6.
![ICMPv6 Ping](https://github.com/kvang138/Wireshark-Capture-Lab/blob/main/Screenshots/ICMPv6%20Ping.png)


### 2. Capturing DNS requests and replies via nslookup openai.com on port 53 over IPv6.
![DNS](https://github.com/kvang138/Wireshark-Capture-Lab/blob/main/Screenshots/DNS.png)

### 3. Capturing a TCP Three-Way Handshake (SYN → SYN+ACK → ACK) during a connection setup between the local machine and the router.
![TCP Three-Way Handshake](https://github.com/kvang138/Wireshark-Capture-Lab/blob/main/Screenshots/TCP%20Three-Way%20Handshake.png)


### 4. Capturing HTTP GET request and response packets on port 80 to and from a local web server on the local machine.
![HTTP on port 80.](https://github.com/kvang138/Wireshark-Capture-Lab/blob/main/Screenshots/HTTP.png)

### 5. Capturing ARP packets on the local network.
  1. The router was inquiring who has one of two logical IP addresses as it attempted to map logical IP addresses to physical MAC addresses.
  2. The local computer was inquiring about the location of the router.

![ARP](https://github.com/kvang138/Wireshark-Capture-Lab/blob/main/Screenshots/ARP.png)

## 🧠🧑‍💻 Hands-on experience in practical network diagnostics and security inspection
  - Captured live network traffic and saved PCAP files for in-depth, repeatable analysis.
  - Applying Wireshark filters (display/capture) to efficiently narrow millions of packets to relevant conversations and anomalies.
  - Examined various protocols and traffic flows (HTTP/S, DNS, TCP retransmissions, TLS handshakes, etc.) to uncover root causes of issues.
  - Conducted real-world troubleshooting of web applications, network performance, and potential threats through packet-level inspection.
  - Produced documentation with annotated packet captures to clearly communicate technical findings.
