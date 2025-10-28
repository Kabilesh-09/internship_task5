Interview Questions and Answers

1. What is Wireshark used for?
Wireshark is a network protocol analyzer used to capture, inspect, and analyze network traffic in real time for troubleshooting and security analysis.

2. What is a packet?
A packet is a unit of data transmitted over a network that includes headers (source, destination, protocol info) and payload (actual data).

3. How to filter packets in Wireshark?
Use display filters like:

ip.addr == 192.168.1.1 → Show traffic from/to a specific IP

tcp or udp → Filter by protocol

http → Show only HTTP packets

4. What is the difference between TCP and UDP?

TCP is connection-oriented, reliable, and ensures data delivery.

UDP is connectionless, faster, but doesn’t guarantee delivery.

5. What is a DNS query packet?
A DNS query packet is a network request sent to a DNS server to resolve a domain name (e.g., google.com) into an IP address.

6. How can packet capture help in troubleshooting?
It helps identify issues like latency, packet loss, misconfigurations, or malicious traffic by showing the exact network communication flow.

7. What is a protocol?
A protocol defines the rules and conventions for communication between network devices, such as HTTP, TCP, UDP, or DNS.

8. Can Wireshark decrypt encrypted traffic?
Yes, but only if decryption keys are available (like SSL/TLS keys). Encrypted traffic cannot be read without proper authorization or keys.
