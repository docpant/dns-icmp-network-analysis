# DNS and ICMP Network Analysis

## Overview
This project analyzes a network connectivity issue affecting the website www.yummyrecipesforme.com.

The investigation focuses on DNS requests sent over UDP and ICMP error responses captured using tcpdump.

## Objective
- Analyze network traffic logs
- Identify affected protocols and services
- Determine the likely cause of the incident
- Document findings in a structured incident report

## Protocols Involved
- UDP
- ICMP
- DNS

## Key Findings
- DNS requests to port 53 failed
- ICMP returned "udp port 53 unreachable"
- The DNS service was likely unavailable or misconfigured

## Outcome
The investigation concluded that the DNS server was unable to receive DNS requests on UDP port 53, preventing users from accessing the website.
