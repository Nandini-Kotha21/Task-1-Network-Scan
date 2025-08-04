# Task-1-Network-Scan
Cyber Security Internship Task 1
# Task 1 - Network Port Scanning using Nmap

## Objective:
The purpose of this task is to perform a TCP SYN Scan on my local network using Nmap to discover open ports on connected devices and understand network exposure.

## Tools Used:
- Nmap v7.94
- Windows 10 Command Prompt

## Steps Performed:
1. Installed Nmap from the official website.
2. Found my local IP range using `ipconfig`.
3. Ran Nmap scan using the command:
4. Saved the scan results into `scan_results.txt`.
5. Analyzed the open ports and their risks.
6. Uploaded all files to this GitHub repository as documentation.

## Summary of Findings:
- Found open ports on Router (192.168.0.1) like HTTP(80), HTTPS(443), DNS(53).
- Detected an Amazon Device (192.168.0.199) with AJP port (8009) open.
- My own system (192.168.0.195) had open ports for database services (MySQL, Oracle, PostgreSQL) and Windows services (NetBIOS, SMB).

## Files in this Repo:
- `scan_results.txt` — Nmap scan results.
- `README.md` — This documentation.

## Key Learnings:
- Understood how to perform basic network reconnaissance using Nmap.
- Learned to identify open ports and understand their associated security risks.
- Practiced documenting findings for cybersecurity tasks.
