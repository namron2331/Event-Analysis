# Event-Analysis

## Objective
To analyze a network capture file to identify significant events or potential security threats using Wireshark and Snort on Windows and Kali Linux virtual machines.

### Skills Learned
- Network Traffic Analysis
  - Conducted detailed packet capture analysis using Wireshark
  - Identified various network protocols and their usage
-Intrusion Detection Systems (IDS)
  - Used Snort to identify and analyze security alerts
  - Configured Snort for intrusion detection and verified alerts
- Forensic Analysis
  - Employed Network Miner for extracting and analyzing data from network captures
  - Utilized Autopsy for forensic examination of captured data
- Protocol Hierarchy Understanding
  - Analyzed protocol hierarchy and identified different types of traffic
  - Differentiated between various protocols like TCP, HTTP, FTP, UDP, and ARP
- Network Security
  -Identified and analyzed security anomalies such as IP spoofing
  - Investigated potential security incidents and determined their impact
- Traffic Pattern Analysis
  - Recognized data transmission spikes and analyzed their causes
  - Used Wireshark I/O graphs to identify peak traffic times
- Technical Documentation
  - Created comprehensive lab reports detailing analysis and findings
  - Documented the process and results for each step of the analysis
- Problem-Solving Skills
  - Diagnosed and solved network-related issues
  - Investigated and provided insights into potential security breaches
- Tool Proficiency
  - Gained hands-on experience with Wireshark, Snort, Network Miner, and Autopsy
  - Leveraged various security tools to perform thorough network analysis
- Network Configuration Understanding
  - Identified network layout and configuration
  - Analyzed local network structure and device interactions



### Tools Used
- Wireshark: For detailed packet analysis.
- Snort: For intrusion detection and alert generation.
- Network Miner: For extracting information from network traffic.
- Autopsy: For forensic analysis of the capture file.

## Steps
Capture File Details (Fig. 1):
- Duration: The session capture lasted 8 minutes and 25 seconds.
- Packets Captured: 2,449 packets were captured.
- Bytes Captured: 811,157 bytes.
  
![image](https://github.com/user-attachments/assets/485b56e2-bdcb-44bc-a895-ce0f0859ea31)

Protocol Hierarchy & Observed Protocols (Fig. 2):
- TCP
- HTTP
- FTP
- UDP
- ARP
  
![image](https://github.com/user-attachments/assets/b16c0119-eaa7-4a5d-a13c-67c87f08cf44)


![image](https://github.com/user-attachments/assets/3239029a-f3c6-494c-9b45-ee1a1613ba6d)





## Conclusion
The network capture analysis provided a detailed overview of the network activity during the session. Key events included a significant data transmission spike, interactions with various ISP sites, and the presence of multiple devices on the local network. The Snort analysis identified multiple alerts, indicating potential security concerns that require further investigation.

This lab demonstrated proficiency in using network analysis tools to monitor, investigate, and report on network traffic and security events.

## Appendix
- Fig. 1: Capture File Properties on Wireshark
- Fig. 2: Protocol Hierarchy on Wireshark
- Fig. 3: Conversations on Wireshark
- Fig. 4: Transmission Spike I/O Graph on Wireshark
- Fig. 5: The PCAP on Network Miner
- Fig. 6: TCP Stream of IP 216.166.24.20 on Wireshark show Credit union
- Fig. 7: Home computer and ip address
- Fig. 8: Anomaly and IP Spoofing attempt on Wireshark
- Fig. 9: PCAP file analyzed with SNORT


*Ref 1: Network Diagram*
