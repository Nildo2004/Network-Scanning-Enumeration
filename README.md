# Network Scanning & Enumeration using Nmap

## Objective
The objective of this project is to perform network scanning and enumeration on a vulnerable target system in order to identify open ports, running services, service versions, and potential attack surfaces.

## Lab Environment
- Attacker Machine: Kali Linux
- Target Machine: Metasploitable 2
- Virtualization Tool: VirtualBox

## Tools Used
- Nmap
- Kali Linux
- Metasploitable 2

## Nmap Commands Used
nmap <target-ip>  
nmap -sV <target-ip>  
nmap -sC -sV -O <target-ip>  

## Key Findings
- Multiple open ports were identified including FTP (21), SSH (22), Telnet (23), and HTTP (80).
- Outdated and insecure services were detected.
- The system exposes a large attack surface due to misconfigurations.

## Conclusion
This project demonstrates how network scanning and enumeration can reveal critical information about a target system. Such information can be leveraged by attackers if proper security controls are not implemented.
