# Nmap Network Scanning Lab

## Objective
Perform network reconnaissance to identify open ports and services on a target system.

## Tools Used
- Kali Linux
- Nmap

## Lab Environment
Attacker Machine: Kali Linux  
Target Machine: Vulnerable Virtual Machine  
Virtualization: VirtualBox

## Methodology

1. Identify target IP address
2. Run Nmap scan to detect open ports
3. Analyze running services
4. Identify potential attack surface

Example command used:

nmap -sV <target-ip>

## Result
Open ports and services were identified, demonstrating how reconnaissance can reveal exposed network services.

## Security Insight
Unnecessary open ports increase attack surface. Proper firewall configuration and service hardening reduce risk.
