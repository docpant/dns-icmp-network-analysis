# Tcpdump Log Analysis

## Traffic Analysis Summary

The tcpdump log captured DNS requests and ICMP error responses between the client system and the DNS server.

The client system (192.51.100.15) repeatedly sent UDP packets to the DNS server (203.0.113.2) requesting the IP address for www.yummyrecipesforme.com using port 53.

Each request received an ICMP error response containing the message “udp port 53 unreachable.”

## Protocols Identified

- UDP: Used to send DNS requests
- DNS: Used to resolve the website domain name
- ICMP: Used to return network error messages

## Key Observations

- Multiple DNS requests failed
- ICMP responses confirmed that port 53 was unreachable
- DNS service was unavailable during the incident
- Users could not access the website because domain resolution failed
