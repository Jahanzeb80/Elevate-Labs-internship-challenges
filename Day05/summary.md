# Day 05 summary 

# Objective
Capture and analyze real-time network traffic using Wireshark to understand common internet protocols and their behavior.


# Summary of Capture
Duration: 60 seconds
Interface: wlan0 
Traffic Generated: `ping 8.8.8.8`, `curl http://subsoft.com` and `https://google.com`
Protocols Observed: HTTP, TCP, DNS, ICMP


# Identified protocol's Roles

# 1.DNS (Domain Name System)**
Purpose: Converts domain names like `google.com` into IP addresses.
Example: A DNS query to `8.8.8.8` asking for the IP of a particualr site.

#2.TCP (Transmission Control Protocol)
Purpose: Ensures reliable data transmission between client and server.
Example: Part of a TCP 3-way handshake (`SYN → SYN-ACK → ACK`) during web requests.

#3.HTTP (Hypertext Transfer Protocol)
Purpose: Protocol used for sending and receiving unencrypted web pages.
Example Packet: HTTP GET request sent to `subsoft.com` via `http://subsoft.com`.

# 4.ICMP (Internet Control Message Protocol)
Purpose: Used for checking if a host is reachable (ping).
Example: ICMP Echo Request and Reply between your system and `8.8.8.8`.


# Conclusion

The packet capture reflects typical internet usage:
DNS: resolved domain names.
TCP: managed connections.
HTTP: handled a basic web request.
ICMP: verified network connectivity.

This hands-on exercise demonstrates how real-world traffic flows across multiple protocols in a short session and helps build packet analysis skills using wireshark.


