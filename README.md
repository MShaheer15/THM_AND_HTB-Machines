# 🎯 HackTheBox Machines — Writeups & Resources

A curated collection of **Hack The Box (HTB)** machine writeup PDFs. These writeups document the enumeration, exploitation, and privilege escalation techniques used to pwn each machine.

> **⚠️ Disclaimer:** All content in this repository is strictly for **educational purposes** and **authorized penetration testing** within the Hack The Box platform. Always ensure you have explicit permission before testing any system.

---

## 📦 Machines

| Machine | OS | Difficulty | Key Techniques |
|---|---|---|---|
| [Remote](./Remote.pdf) | 🪟 Windows | Easy | NFS Enumeration, Umbraco CMS RCE, TeamViewer Exploitation |
| [Sauna](./Sauna.pdf) | 🪟 Windows | Easy | AS-REP Roasting, Kerberos, AutoLogon Creds, DCSync |
| [Search](./Search.pdf) | 🪟 Windows | Hard | Kerberoasting, Password Spraying, GMSA, PKCS#12 Certificates |
| [Shoppy](./Shoppy.pdf) | 🐧 Linux | Easy | NoSQL Injection, Mattermost, Binary Reverse Engineering, Docker Privilege Escalation |
| [Support](./Support.pdf) | 🪟 Windows | Easy | SMB Enumeration, .NET Reverse Engineering, LDAP, Resource-Based Constrained Delegation |

---

## 🗂️ Repository Structure

```
HTB-Boxes-Resources/
├── README.md                  # This file
├── Remote.pdf                 # Remote machine writeup
├── Sauna.pdf                  # Sauna machine writeup
├── Search.pdf                 # Search machine writeup
├── Shoppy.pdf                 # Shoppy machine writeup
└── Support.pdf                # Support machine writeup
```

---

## 🛠️ Common Tools Used

| Category | Tools |
|---|---|
| Reconnaissance | `nmap`, `gobuster`, `ffuf`, `enum4linux` |
| Active Directory | `BloodHound`, `SharpHound`, `Impacket`, `Rubeus` |
| Credential Attacks | `Hashcat`, `John the Ripper`, `GetNPUsers.py`, `GetUserSPNs.py` |
| Exploitation | `Metasploit`, `evil-winrm`, `psexec.py`, `wmiexec.py` |
| Post-Exploitation | `winPEAS`, `linPEAS`, `PowerView`, `Mimikatz` |

---

## 🚀 Getting Started

1. Sign up at [Hack The Box](https://www.hackthebox.com/)
2. Connect to the HTB VPN
3. Reference these writeup PDFs as learning material after attempting the machines yourself
4. Practice the techniques in a safe, authorized environment

---

<p align="center">
  <b>Happy Hacking! 🐱‍💻</b>
</p>
