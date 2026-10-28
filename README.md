# Active Directory & PrivEsc Cheatsheets

Personal reference collection built from CTF rooms, labs, and authorized engagements — Active Directory attack paths, Windows/Linux privilege escalation, credential harvesting, and post-exploitation techniques.

> ⚠️ For authorized labs, CTFs, and engagements only. Not a how-to for unauthorized access.

## Structure

| Folder | Covers |
|---|---|
| `1-Enumeration` | AD enumeration, attack playbook, hidden-enum techniques |
| `2-File Transfer` | Windows ⇄ Kali file transfer methods |
| `3-Exploitation` | ACL abuse, Kerberos delegation (unconstrained/constrained/RBCD), NTLM relay, GPO abuse, AD CS (ESC1–ESC13), domain trust attacks |
| `4-Persistence` | Golden/Silver tickets, AD CS certificate persistence |
| `5-Credential-Harvesting` | LSASS dumping, local Windows credentials |
| `6-Proxy` | Pivoting & port forwarding |
| `7-Bloodhound` | BloodHound setup & usage |
| `8-windows-machine` | Standalone Windows box walkthroughs |
| `9-DMSA` | dMSA / Shadow Credentials attacks |
| `10-Linux-Privilegeescaltion` | Linux PrivEsc cheatsheet |
| `11-WindowsPrivilege-escalation` | Windows PrivEsc cheatsheet (service misconfig, token abuse, UAC bypass, UDF, cross-compiling) |

## Usage

Open any `.html` file directly in a browser — each is self-contained with no external dependencies.

## Disclaimer

This repository is for educational purposes and authorized security testing only. The author is not responsible for misuse.
