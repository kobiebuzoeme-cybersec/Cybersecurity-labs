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
nmap -sn <target-ip>
nmap -A-T4 <target-ip>

## Result
Open ports and services were identified, demonstrating how reconnaissance can reveal exposed network services.

## Security Insight
Unnecessary open ports increase attack surface. Proper firewall configuration and service hardening reduce risk.

## Related Screenshots for Nmap
<img width="1239" height="308" alt="Screenshot 2025-11-19 100549" src="https://github.com/user-attachments/assets/c1a6b743-1d2c-4fb9-a1c3-3e2b11c9bd52" />
<img width="795" height="257" alt="image" src="https://github.com/user-attachments/assets/8fbf181f-a601-407f-bd40-78cb08f5d0ce" />



