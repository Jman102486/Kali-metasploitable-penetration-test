# Kali Linux vs Metasploitable 2 - Penetration Testing Lab

## Overview
This project demonstrates a full penetration testing workflow conducted in a controlled lab enviroment using Kali Linux and Metasploitable 2.

The objective was to identify vulnerabilities, exploit them, gain root access, and perform post-exploitation analysis.

---

## Tools Used
-Kali Linux
- Metasploitable 2
- Nmap
- Metasploit Framework

---

## Lab Setup
- VirtualBox virtual enviroment
- Host-only network configuration
- Troubleshot network connectivity issues between attacker and target machines

---

## Reconnaissance

Performed service and version detection using:

	nmap -sV 192.168.56.101
