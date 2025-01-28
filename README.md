### Lab Project: Wireshark Network Traffic Analysis

---

## Project Overview
This lab project focuses on using Wireshark, a network protocol analyzer, to capture and analyze network traffic. By monitoring packet exchanges, you will gain insights into network protocols, packet structures, and communication patterns.

---

## Objectives
- Understand how to capture and analyze network traffic using Wireshark.
- Identify specific packet types, including ICMP, TCP, and UDP.
- Observe and analyze protocol-specific details like handshakes, data transfers, and error messages.

---

## Lab Tasks

### 1. **Installing and Setting Up Wireshark**
   - Ensure Wireshark is installed on your system.
   - Launch Wireshark with appropriate permissions:
     ```bash
     sudo wireshark
     ```
   - Select the network interface to monitor (e.g., eth0 or wlan0).

---

### 2. **Capturing Network Traffic**
   - Start a capture session by clicking the **Start Capturing Packets** button.
   - Perform specific network actions such as:
     - Pinging another machine using ICMP:
       ```bash
       ping <IP Address>
       ```
     - Establishing a connection using TCP (e.g., opening a web page or SSH session).
     - Sending a UDP-based query (e.g., DNS lookup).

---

### 3. **Applying Filters**
   - Use display filters in Wireshark to narrow down traffic:
     - ICMP packets:
       ```plaintext
       icmp
       ```
     - TCP packets:
       ```plaintext
       tcp
       ```
     - UDP packets:
       ```plaintext
       udp
       ```

---

### 4. **Analyzing Captured Traffic**
   - Observe the details of specific packets, such as:
     - Source and destination IP addresses.
     - Protocol used.
     - Payload data.
   - For ICMP traffic, identify request and reply messages.
   - For TCP traffic, analyze the three-way handshake (SYN, SYN-ACK, ACK).
   - For UDP traffic, observe DNS queries and responses.

---

### 5. **Saving Captures**
   - Save the captured data for later review:
     ```plaintext
     File > Save As > <filename>.pcap
     ```

---

## Deliverables
1. Saved Wireshark capture files (.pcap) demonstrating ICMP, TCP, and UDP traffic.
2. Screenshots of packet details for each protocol type.
3. Observations on the captured traffic, including protocol behavior and communication patterns.

---

## Notes
- Ensure network interfaces are active and have traffic for meaningful captures.
- Use filters to focus on specific traffic types.
- Familiarize yourself with Wireshark's interface and features for efficient analysis.

---
