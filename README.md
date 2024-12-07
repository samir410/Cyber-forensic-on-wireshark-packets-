# Cyber-forensic-on-wireshark-packets-

Here's a README.md for the CYFO Network Forensics Lab Assignment:

🔍 CYFO Network Forensics Lab Assignment 🛡️
Stockholm University
Course: Cyber Forensics (CYFO)
Department: Computer and Systems Sciences
Date: April 2024

🌟 Overview
This lab assignment focuses on network forensics, specifically analyzing captured network traffic files (pcap files) to investigate potential cyberattacks. The investigation aims to identify suspicious activities, such as SYN flood attacks, ARP poisoning, and port scanning. The lab covers the methodologies for ensuring file integrity, analyzing network traffic, and interpreting the results of forensic analysis.

Team Members:

Samir Hossain Santo Bepu
Pavan Gupta
🖥️ Assignment Breakdown
Assignment 1: SYN Flood Attack Analysis
Objective: Analyze pcap files for suspicious traffic and identify potential attacks.
Findings:
Attack Type: SYN flood, where attackers overwhelm the server with incomplete connection attempts, causing a Denial of Service (DoS).
Source IPs: Multiple sources including 192.0.2.245, 192.0.2.154.
Destination IP: 192.0.2.2
Protocol: TCP (Transport Layer)
Assignment 2: ARP Poisoning Attack
Objective: Investigate the ARP protocol and identify signs of ARP poisoning.
Findings:
Source MAC Address: 00:11:22:33:44:55
Destination MAC Address: 00:0e:0c:83:13:e8
Attack Type: ARP Poisoning, enabling attacks like Man-in-the-Middle (MITM), session hijacking, and Denial of Service (DoS).
Assignment 3: SYN Scanning
Objective: Detect reconnaissance activity through SYN scanning.
Findings:
Source IP: 10.0.23.109
Destination IP: 80.237.98.132
Attack Type: SYN scanning, which is used to discover open ports and potentially vulnerable services.
🛠️ Methodology
Hash Integrity Checks: Ensured integrity of evidence files using MD5 and SHA1 hashes.
Network Traffic Analysis: Tools such as Wireshark were used to capture and analyze suspicious traffic, identify malicious patterns, and investigate attack vectors.
Forensic Tools: Commands such as md5sum and sha1sum were utilized to confirm file integrity.
📊 Key Tools & Protocols
Wireshark: For deep network traffic analysis.
MD5/SHA1 Hashing: To ensure the integrity of the captured pcap files.
ARP: To investigate link-layer protocols.
TCP/IP: Protocols critical in analyzing SYN flood and SYN scanning activities.
🛡️ Conclusion
Through the analysis of captured network traffic, this forensic investigation highlighted various cyberattacks, including SYN flood, ARP poisoning, and SYN scanning. These attacks, if left unchecked, could lead to severe service disruptions, data breaches, or unauthorized network access. The findings demonstrate the importance of continuous monitoring and robust defensive mechanisms in network environments.

