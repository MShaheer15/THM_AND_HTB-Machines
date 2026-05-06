# 🎯 HackTheBox & TryHackMe Machines — Writeups & Resources

A curated collection of **Hack The Box (HTB)** and **TryHackMe (THM)** machine writeup PDFs. These writeups document the enumeration, exploitation, and privilege escalation techniques used to pwn each machine.

> **⚠️ Disclaimer:** All content in this repository is strictly for **educational purposes** and **authorized penetration testing** within the Hack The Box and TryHackMe platforms. Always ensure you have explicit permission before testing any system.

---

## 📦 Machines

| Machine | Platform | OS | Difficulty | Key Techniques |
|---|---|---|---|---|
| [Remote](./Remote.pdf) | HTB | 🪟 Windows | Easy | NFS Enumeration, Umbraco CMS RCE, TeamViewer Exploitation |
| [Sauna](./Sauna.pdf) | HTB | 🪟 Windows | Easy | AS-REP Roasting, Kerberos, AutoLogon Creds, DCSync |
| [Search](./Search.pdf) | HTB | 🪟 Windows | Hard | Kerberoasting, Password Spraying, GMSA, PKCS#12 Certificates |
| [Shoppy](./Shoppy.pdf) | HTB | 🐧 Linux | Easy | NoSQL Injection, Mattermost, Binary Reverse Engineering, Docker Privilege Escalation |
| [Support](./Support.pdf) | HTB | 🪟 Windows | Easy | SMB Enumeration, .NET Reverse Engineering, LDAP, Resource-Based Constrained Delegation |
| [Ledger](./THM_Ledger.pdf) | THM | 🪟 Windows | Hard | AD CS Misconfiguration (ESC1), Certificate Templates, LDAP Enumeration |
| [K2 Base Camp](./K2/THM_K2__Base_Camp.pdf) | THM | 🐧 Linux | Hard | Web Enumeration, Blind XSS, WAF Bypass, SQL Injection, Post-Exploitation |
| [K2 Middle Camp](./K2/THM_K2_Middle_Camp.pdf) | THM | 🐧 Linux/Windows | Hard | Intermediate Escalation, Information Gathering |
| [K2 The Summit](./K2/THM_K2_The_Summit.pdf) | THM | 🪟 Windows | Hard | AD Enumeration, BloodHound, RBCD, Pass-the-Ticket, Domain Admin |

---

## 🗂️ Repository Structure

```
HTB-Machines-/
├── README.md                  # This file
├── K2/                        # TryHackMe K2 Series
│   ├── THM_K2__Base_Camp.pdf
│   ├── THM_K2_Middle_Camp.pdf
│   └── THM_K2_The_Summit.pdf
├── Remote.pdf                 # HTB Remote machine writeup
├── Sauna.pdf                  # HTB Sauna machine writeup
├── Search.pdf                 # HTB Search machine writeup
├── Shoppy.pdf                 # HTB Shoppy machine writeup
├── Support.pdf                # HTB Support machine writeup
└── THM_Ledger.pdf             # THM Ledger machine writeup
```

---

## 🛠️ Common Tools Used

| Category | Tools |
|---|---|
| Reconnaissance | `nmap`, `gobuster`, `ffuf`, `enum4linux` |
| Active Directory | `BloodHound`, `SharpHound`, `Impacket`, `Rubeus`, `Certipy` |
| Credential Attacks | `Hashcat`, `John the Ripper`, `GetNPUsers.py`, `GetUserSPNs.py` |
| Exploitation | `Metasploit`, `evil-winrm`, `psexec.py`, `wmiexec.py` |
| Post-Exploitation | `winPEAS`, `linPEAS`, `PowerView`, `Mimikatz` |

---

## 🚀 Getting Started

1. Sign up at [Hack The Box](https://www.hackthebox.com/) and [TryHackMe](https://tryhackme.com/)
2. Connect to the respective VPNs
3. Reference these writeup PDFs as learning material after attempting the machines yourself
4. Practice the techniques in a safe, authorized environment

---

<p align="center">
  <b>Happy Hacking! 🐱‍💻</b>
</p>
