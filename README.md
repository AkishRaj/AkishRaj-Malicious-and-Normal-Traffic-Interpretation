# AkishRaj-Malicious-and-Normal-Traffic-Interpretation
## Introduction
In today’s digital landscape, distinguishing between malicious and normal
network traffic is critical for ensuring cybersecurity. Malicious traffic poses
serious threats to systems, while normal traffic follows routine communication
patterns. This investigation aims to explore the key methods for detecting
malicious traffic and the challenges involved in differentiating it from
legitimate activity, ultimately contributing to stronger network defense
strategies.

##Problem Statement
In this modern Era Distinguishing between malicious and normal traffic is critical
for maintaining security and operational integrity. The increasing volume and
complexity of network traffic make it challenging to accurately identify and
interpret malicious activities without generating excessive false positives or
impacting legitimate operations.

##Objective
Employ tools like Wireshark to capture and inspect network traffic for forensic purposes.
Use Wireshark to detect and categorize different types of attack signatures and network
anomalies. Enable administrators to monitor network activity at a granular level, gaining
insights into real-time events.

##Workflow Diagram
![image](https://github.com/user-attachments/assets/56ec2868-3a3c-4bdc-a1cc-0404306d5fda)

##Methodology
Data Collection: Capture real-time network traffic using Wireshark,
storing it in PCAP files. This traffic will contain both normal and
potentially harmful packets.

Data Filtering: Leverage Wireshark’s advanced filtering capabilities to
detect anomalies in the network, such as malware, suspicious behaviors, or
slow connections. Automated Traffic Capture: Use TShark to automate
the traffic capture process, enabling continuous monitoring of network
activity.

Geolocation Mapping: Utilize Python, along with libraries like Pyshark
and Geopy, to analyze the PCAP data and visually map the destination IP
addresses.

Testing and Validation: Perform testing across different network
environments to assess the effectiveness of the methodology in detecting
network issues and malicious activities.

##IMPLEMENTATION
1. Setup Environment: Install Wireshark and Tshark on your Linux
machine, ensuring you have the necessary permissions to capture network
traffic.

2. Monitoring network traffic: it provides detailed information such as
timestamps, frame numbers, and packet sizes. At the network layer, it
reveals source and destination MAC addresses, IP addresses, and protocols
(like TCP, UDP, or ICMP). You can also see transport layer details like
port numbers, packet flags, sequence numbers, and payload data, helping
analyze network communication and detect issues like latency, dropped
packets, or security threats

3. Running Malware: DDoS and ARP Poisoning: When malware initiates
a DDoS (Distributed Denial of Service) attack, Wireshark captures high
volumes of traffic targeting specific IP addresses, often overwhelming a
server with numerous requests. In ARP poisoning, Wireshark detects
manipulated ARP packets where the malware alters MAC-to-IP mappings,
redirecting network traffic.

4. Capturing malware traffic: When running malware in a controlled
environment and capturing the network traffic with Wireshark, you can
observe malicious activities like unusual connections, abnormal traffic
patterns, or data exfiltration attempts.

5. Automating Network Analysis with Tshark: By automating Tshark,
you can efficiently scan live network traffic and analyze PCAP files.
Tshark's filters allow you to capture specific packets or protocols in
real-time, and automation scripts can quickly process and extract key
information, such as IP addresses or unusual traffic patterns, from stored
capture files. This makes network monitoring and malware detection more
streamlined and less reliant on manual analysis.

##RESULT AND OUTPUT
![image](https://github.com/user-attachments/assets/a48b3c1c-a6ca-4814-b33d-7a2afe168a2f)

![image](https://github.com/user-attachments/assets/9c8d4d82-ba68-4f19-948b-eccc574cb39a)

![image](https://github.com/user-attachments/assets/3d13c444-216a-4c72-a26a-e1724cb5006f)

![image](https://github.com/user-attachments/assets/a7c46dd1-fddd-443f-8e11-6458a826b731)

![image](https://github.com/user-attachments/assets/75f9ab2b-9703-45ea-91d7-222a74a164fa)

![image](https://github.com/user-attachments/assets/cdabf30d-d466-47ff-8390-9b8c9206ccda)

## Conclusion
The project proved that it is possible to capture, analyze, and visual
network traffic with Wireshark, Python, and TShark. By assisting the
automated process of traffic capture while mapping geolocation
information, a clear approach is provided that assists in identifying what is
normal traffic and what is suspected to be malicious in nature. Since this
system also incorporates the analysis of data in real-time, it helps in the
monitoring of networks and quicker resolution of cybersecurity issues.





