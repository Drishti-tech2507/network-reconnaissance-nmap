# Network Reconnaissance Using Nmap (Router Scan)

## Objective
To perform network reconnaissance on a local network router using Nmap in order to identify live hosts, open ports, running services, and potential entry points.

## Tools Used
- Kali Linux
- Nmap

## Network Details
- Local Network: 192.168.x.0/24
- Target Device: Network Router
- Target IP: 192.168.x.1

## Commands Used
```bash
ip a
nmap -sn 192.168.x.0/24
nmap -A -T4 192.168.x.1
