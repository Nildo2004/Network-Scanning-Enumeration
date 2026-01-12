# Network Scanning & Enumeration using Nmap

## Objective
The objective of this project is to perform network scanning and enumeration on a vulnerable target system in a controlled lab environment. The project aims to identify open ports, running services, service versions, and potential attack surfaces using industry-standard tools.

---

## Lab Environment
- **Attacker Machine:** Kali Linux  
- **Target Machine:** Metasploitable 2  
- **Virtualization Tool:** VirtualBox  

---

## Tools Used
- **Nmap** – Network scanning and service enumeration  
- **Kali Linux** – Penetration testing platform  
- **Metasploitable 2** – Vulnerable target system  

---

## Nmap Commands Used
- `nmap` – Basic port scanning  
- `nmap -sV` – Service and version detection  
- `nmap -sC -sV -O` – Default scripts, service enumeration, and OS detection  

---

## Key Findings
- Multiple open ports were identified, including:
  - FTP (21)
  - SSH (22)
  - Telnet (23)
  - HTTP (80)
- Several outdated and insecure services were detected.
- The system exposes a large attack surface due to insecure configurations and unnecessary open services.

---

## Attack Surface Summary
Exposed network services such as FTP, Telnet, and HTTP significantly increase the attack surface of the target system. If left unsecured, these services could allow attackers to perform further enumeration, credential attacks, or remote exploitation.

---

## Conclusion
This project demonstrates how network scanning and enumeration can reveal critical information about a target system. Identifying open ports and exposed services is a crucial first step in penetration testing. Proper security measures such as disabling unnecessary services, applying patches, and configuring firewalls can greatly reduce potential security risks.

---

## Disclaimer
This project was conducted in a controlled lab environment for educational purposes only. Unauthorized scanning of networks without explicit permission is illegal and unethical.
