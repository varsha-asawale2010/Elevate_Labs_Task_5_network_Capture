# Elevate_Labs_Task_5_Network_Capture
## task name: Capture and Analyze Network Traffic Using Wireshark.
## Installation Sucussfull
![image](https://github.com/user-attachments/assets/f2ba3fcf-33be-4418-81be-458fe5cf79b1)
## Start Capturing using wireshark
![image](https://github.com/user-attachments/assets/7da4d118-376d-4da0-bbd5-4852be38c21d)
## Ping server and generate some traffic
## ping website name:github.com
![image](https://github.com/user-attachments/assets/72c27944-ba8a-4624-bae8-14de8b27143c)

## Filter captured packets by protocol
Protocol 1:- http-hyper text transfer protocol
![image](https://github.com/user-attachments/assets/bbd751ee-fe57-4609-b18d-340dd0d69b09)

protocol 2:- DNS-Domain name server
![image](https://github.com/user-attachments/assets/bb0eede6-8dec-424c-a56d-ca1e2784b153)

Protocol 3:- tcp-Transmission Control Protocol
![image](https://github.com/user-attachments/assets/8211419f-b480-4098-8756-712fe25a45ba)

 Protocol 4:- ICMP-Internet Control Message Protoco
![image](https://github.com/user-attachments/assets/86e6c35b-8e30-4f3d-8ebc-778d6528659f)

## Identify at Least 3 Different Protocols

DNS (Domain Name System):Translates domain names github.com into  their IP addresses.
Look for packets where your computer queries a DNS server to resolve a domain name.

HTTP (Hypertext Transfer Protocol): Used for transferring web pages.
Identify HTTP GET or POST requests when accessing websites.

TCP (Transmission Control Protocol): Establishes and maintains a connection between devices for data transmission.
Notice the three-way handshake (SYN, SYN-ACK, ACK) when initiating a connection.

ICMP (Internet Control Message Protocol):Used for diagnostic purposes, like the ping command.
See echo request and reply packets when you ping a server.

## Export the capture here



## 8. Summarize our Findings and Packet Details
DNS Queries: Your computer sent DNS queries to resolve domain names, receiving corresponding IP addresses in the responses.
HTTP Requests: When accessing websites, HTTP GET requests were sent, and responses were received, containing the requested web pages.
TCP Handshakes: Before data transmission, TCP connections were established using the three-way handshake process.
ICMP Packets: Using the ping command generated ICMP echo request and reply packets, indicating connectivity with the target server.






