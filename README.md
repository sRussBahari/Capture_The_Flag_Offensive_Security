# Capture_The_Flag_Offensive_Security
Date: Jul 2023

## Overview of the Offensive Security Project
Participated in a rigorous Capture the Flag (CTF) exercise of a fictive company Rekall Corporation (totalrekall.xyz), utilizing advanced offensive security techniques to uncover and exploit vulnerabilities within a simulated organization environment

## Key Achievements
- Detected and acted upon security flaws in the organization's web application, securing competition flags as proof of successful penetration
- Demonstrated proficiency in endpoint security by launching a targeted attack on Rekall's Linux servers, tapping into Linux-specific vulnerabilities to access critical data and capture competition flags
- Pivoted strategies to target Rekall’s Windows servers, employing in-depth knowledge of Windows OS vulnerabilities to infiltrate the system and seize additional flags

## Technologies used
-Kali Linux
-Nessus
-Windows Operating System
-Linux Operating System

## Screenshots
I) Web Application vulnerabilities


1) -XSS payload
![XSS_payload](./XSS_payload.png)

2) -Php script uploaded to get the flag 
![Php_Script1](./Php_script_1.png)
![Php_Script2](./Php_script_2.png)

3) -Robot exclusion protocol (robots.txt)
![REP](./Robot_exclusion_protocol.png)


II) Linux Server vulnerabilities

1) -SSL certificate, use of "crt.sh" and look up for totalrekall.xyz for the flag.
![SSL](./Certificate_flag.png)

2) -Nmap agressive scan on every IP address on the domain totalrekall.xyz with an IP address of 192.168.13.0/24 as the flag is the IP address running the Drupal service. The flag was the following IP address 192.168.13.13
![Nmap_Aggressive_scan](./Nmap_Scan_1.png)
![Nmap_Aggressive_scan](./Nmap_Scan_2.png)

3) -Use of Metasploit to find an exploit on the Linux server and navigate to the root folder within the shell to get the flag.
![Metasploit](./Metasploit_1.png)
![Metasploit](./Metasploit_2.png)




III) Windows Server vulnerabilities
