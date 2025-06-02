Report: Wireshark Network Traffic Analysis

Internship Task: Task 5 - Capture and Analyze Network Traffic  
Date of Capture: June 2, 2025  
Time: 1:15 PM to 1:16 PM  
Capture Tool: Wireshark  
Interface Used: Wi-Fi


Summary of Capture

Total Packets Captured: 2997
Duration of Capture: 60 seconds
File Saved As:`network-capture.pcap`
Location: Local PC folder, also uploaded to GitHub

Protocols Identified

 1. HTTP (Hypertext Transfer Protocol)
Function: Used for transferring web pages and web-based content.
Observation: Captured HTTP GET request to `example.com`.
Common Port: 80
Example Packet Info:
 
  GET / HTTP/1.1
  Host: google.com
  
2. DNS (Domain Name System)
Function: Resolves human-readable domain names into IP addresses.
Observation: Captured DNS query for `google.com`.
Common Port:53
Example Packet Info:
  
 Standard query 0x1234 A google.com
  
3. TCP (Transmission Control Protocol)
Function: Provides reliable, ordered, and error-checked delivery of data.
Observation: Observed TCP 3-way handshake and HTTP data exchange.
Common Port: 80 (HTTP), 443 (HTTPS)
Example Packet Info:
  
  [SYN] Seq=0 Win=64240 Len=0 MSS=1460
  [SYN, ACK] Seq=0 Ack=1
  [ACK] Seq=1 Ack=1
  ```
 Screenshots Included

All screenshots are available in the `screenshots/` folder:
interface-selected.png
filter-http.png
filter-dns.png
filter-tcp.png
export-pcap.png

---

 Conclusion

This task helped gain hands-on experience with:
 Capturing live traffic using Wireshark
 Analyzing common protocols (HTTP, DNS, TCP)
 Using filters to isolate and inspect packet types

The `.pcap` file and this report provide a clear overview of the captured traffic and network behavior.



Prepared by: 
Suhani Pandey  
Cyber Security Internship – Task 5