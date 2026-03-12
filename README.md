# Cybersecurity Lab Work — Lavanya M

## About
This repository contains hands-on cybersecurity lab work completed 
as part of the **IIT Ropar Cyber Security Essentials Certification 
Programme** (in association with TCS iON), for which I received a 
**Certificate of Excellence**.

---

## Penetration Testing Lab Report

A practical penetration testing exercise performed in a controlled 
Docker-based virtual lab environment using industry-standard tools.

### Lab Environment
| Component | Details |
|-----------|---------|
| Attacker Machine | Metasploit Framework — IP: 11.0.0.5 |
| Victim Machine | Metasploitable2 — IP: 11.0.0.7 |
| Network | Isolated Docker virtual network (11.0.0.0/24) |

### Tools Used
- **Docker** — Lab environment setup
- **Nmap** — Network scanning and host enumeration
- **Metasploit Framework** — Exploitation framework
- **Metasploitable2** — Intentionally vulnerable target machine

### Exercises Covered
| # | Exercise | Tool/Module |
|---|----------|-------------|
| 1 | Network Scanning with Nmap | nmap -A |
| 2 | FTP Backdoor Exploitation (vsftpd 2.3.4) | exploit/unix/ftp/vsftpd_234_backdoor |
| 3 | PHP-CGI Argument Injection | exploit/multi/http/php_cgi_arg_injection |
| 4 | UnrealIRCd Backdoor Exploitation | exploit/unix/irc/unreal_ircd_3281_backdoor |
| 5 | Slowloris DoS Attack Simulation | auxiliary/dos/http/slowloris |

### Key Findings
- Multiple open ports with outdated services on target machine
- Successfully gained root shell via FTP backdoor
- Successfully opened reverse shell via PHP-CGI injection
- Successfully exploited IRC backdoor for remote command execution
- Successfully demonstrated DoS attack exhausting server connections

---

## Certifications
- **Certificate of Excellence** — Cyber Security Essentials 
  Certification Programme, IIT Ropar (TCS iON) — January 2026
- **Cybersecurity Job Simulation** — Mastercard, Forage — March 2026

---

## Disclaimer
All exercises were performed in an **isolated, controlled lab 
environment for educational purposes only**. No real systems 
were targeted or harmed.
