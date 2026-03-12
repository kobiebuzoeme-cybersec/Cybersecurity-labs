# Netcat Banner Grabbing Lab

## Objective
Identify service information running on a target machine.

## Tools Used
- Kali Linux
- Netcat

## Method

1. Identify open port from Nmap scan
2. Connect using Netcat
3. Capture service banner

Example command:

nc <target-ip> <port>

## Result
Service information was retrieved from the target system.

## Security Lesson
Banner information reveals software versions that attackers can use to identify vulnerabilities.
