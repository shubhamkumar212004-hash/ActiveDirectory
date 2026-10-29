# Active Directory & PrivEsc Cheatsheets

Personal reference collection built from CTF rooms, labs, and authorized engagements — Active Directory attack paths, Windows/Linux privilege escalation, credential harvesting, and post-exploitation techniques.

> ⚠️ For authorized labs, CTFs, and engagements only. Not a how-to for unauthorized access.

🌐 **Live site:** https://shubhamkumar212004-hash.github.io/ActiveDirectory/

## 1 — Enumeration
- [AD Attack Playbook](https://shubhamkumar212004-hash.github.io/ActiveDirectory/1-Enumeration/AD%20Attack%20Playbook.html)
- [AD Enumeration — Master Field Reference](https://shubhamkumar212004-hash.github.io/ActiveDirectory/1-Enumeration/AD%20Enumeration%20%E2%80%94%20Master%20Field%20Reference.html)
- [hidden-enum](https://shubhamkumar212004-hash.github.io/ActiveDirectory/1-Enumeration/hidden-enum.html)

## 2 — File Transfer
- [File Transfer Cheatsheet](https://shubhamkumar212004-hash.github.io/ActiveDirectory/2-File%20Transfer/File%20Transfer%20Cheatsheet.html)
- [Windows ⇄ Kali File Transfer Cheat Sheet](https://shubhamkumar212004-hash.github.io/ActiveDirectory/2-File%20Transfer/Windows%20%E2%87%84%20Kali%20File%20Transfer%20Cheat%20Sheet.html)
- [windows_to_kali_file_transfer_guide.pdf](https://shubhamkumar212004-hash.github.io/ActiveDirectory/2-File%20Transfer/windows_to_kali_file_transfer_guide.pdf)

## 3 — Exploitation

**ACL Abuse**
- [ACL_abuse1](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/0-ACL/ACL_abuse1.html)
- [ACL_abuse2](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/0-ACL/ACL_abuse2.html)
- [DATASPACE.LOCAL Walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/0-ACL/DATASPACE.LOCAL%20Walkthrough.html)
- [GenericWrite — Complete Attack Mindmap](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/0-ACL/GenericWrite%20%E2%80%94%20Complete%20Attack%20Mindmap.html)

**Kerberos Delegation**
- [Unconstrained Delegation — Testing Methodology](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/1-kerberos_delegation/1unconstrained_delegation/Unconstrained%20Delegation%20%E2%80%94%20Testing%20Methodology.html)
- [1_Constrained Delegation Abuse — POC Walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/1-kerberos_delegation/2constarined_delegation/1_Constrained%20Delegation%20Abuse%20%E2%80%94%20POC%20Walkthrough.html)
- [2_Constarined_CIFS Delegation Attack — Commands](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/1-kerberos_delegation/2constarined_delegation/2_Constarined_CIFS%20Delegation%20Attack%20%E2%80%94%20Commands.html)
- [Constrained Delegation Walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/1-kerberos_delegation/2constarined_delegation/Constrained%20Delegation%20Walkthrough.html)
- [TryHackMe _Reset_ — Full AD Walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/1-kerberos_delegation/2constarined_delegation/TryHackMe%20_Reset_%20%E2%80%94%20Full%20AD%20Walkthrough.html)
- [RBCD — Resource-Based Constrained Delegation Walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/1-kerberos_delegation/3RBCD/RBCD%20%E2%80%94%20Resource-Based%20Constrained%20Delegation%20Walkthrough.html)
- [RBCD_Complete_Guide_All_Techniques_Mindmap](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/1-kerberos_delegation/3RBCD/RBCD_Complete_Guide_All_Techniques_Mindmap.html)
- [RBCD_PoC_Full](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/1-kerberos_delegation/3RBCD/RBCD_PoC_Full.html)

**NTLM Relay**
- [Machine-Account-Relay](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/2-Ntlmrelay/Machine-Account-Relay.html)

**User AD Exploitation**
- [AD-User-Exploitation-Walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/3-User-ad-exploit/AD-User-Exploitation-Walkthrough.html)

**GPO**
- [GPO-Abuse](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/4-GPO/GPO-Abuse.html)

**Certificate Services (ADCS)**
- [ADCS Attack Paths — ESC1 to ESC13](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/5-Certificate/ADCS%20Attack%20Paths%20%E2%80%94%20ESC1%20to%20ESC13.html)
- [ESC1 Certificate Attack](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/5-Certificate/ESC1/ESC1%20Certificate%20Attack.html)
- [ESC1_ADCS_Walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/5-Certificate/ESC1/ESC1_ADCS_Walkthrough.html)

**Domain Trust**
- [ZA Forest Compromise](https://shubhamkumar212004-hash.github.io/ActiveDirectory/3-Exploitation/6-DOMAIN%20TRUST/ZA%20Forest%20Compromise.html)

## 4 — Persistence
- [0-persisting_ad_walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/4-Persistence/0-persisting_ad_walkthrough.html)
- [1-golden-silver](https://shubhamkumar212004-hash.github.io/ActiveDirectory/4-Persistence/1-golden-silver.html)
- [AD CS Certificate Persistence](https://shubhamkumar212004-hash.github.io/ActiveDirectory/4-Persistence/2-AD%20CS%20Certificate%20Persistence.html)

## 5 — Credential Harvesting
- [Local Windows Credentials & LSASS](https://shubhamkumar212004-hash.github.io/ActiveDirectory/5-Credential-Harvesting/Local%20Windows%20Credentials%20%26%20LSASS.html)
- [Other AD _ Network Attacks — Full Steps](https://shubhamkumar212004-hash.github.io/ActiveDirectory/5-Credential-Harvesting/Other%20AD%20_%20Network%20Attacks%20%E2%80%94%20Full%20Steps.html)

## 6 — Proxy
- [Pivoting & Port Forwarding — Field Reference](https://shubhamkumar212004-hash.github.io/ActiveDirectory/6-Proxy/Pivoting%20%26%20Port%20Forwarding%20%E2%80%94%20Field%20Reference.html)

## 7 — Bloodhound
- [BloodHound — Complete Setup & Troubleshooting Guide](https://shubhamkumar212004-hash.github.io/ActiveDirectory/7-Bloodhound/BloodHound%20%E2%80%94%20Complete%20Setup%20%26%20Troubleshooting%20Guide.html)

## 8 — Windows Machine Walkthroughs
- [checkpoint-child.pdf](https://shubhamkumar212004-hash.github.io/ActiveDirectory/8-windows-machine/checkpoint-child.pdf)
- [Checkpoint](https://shubhamkumar212004-hash.github.io/ActiveDirectory/8-windows-machine/Checkpoint.html)
- [touch-htb-walkthrough](https://shubhamkumar212004-hash.github.io/ActiveDirectory/8-windows-machine/touch-htb-walkthrough.html)
- [TryHackMe _Reset](https://shubhamkumar212004-hash.github.io/ActiveDirectory/8-windows-machine/TryHackMe%20_Reset.html)

## 9 — DMSA
- [dMSA_Attacks_ShadowCredentials_Cheatsheet](https://shubhamkumar212004-hash.github.io/ActiveDirectory/9-DMSA/dMSA_Attacks_ShadowCredentials_Cheatsheet.html)

## 10 — Linux Privilege Escalation
- [Linux PrivEsc Cheatsheet](https://shubhamkumar212004-hash.github.io/ActiveDirectory/10-Linux-Privilegeescaltion/Linux%20PrivEsc%20Cheatsheet.html)

## 11 — Windows Privilege Escalation
- [Windows PrivEsc Cheatsheet](https://shubhamkumar212004-hash.github.io/ActiveDirectory/11-WindowsPrivilege-escalation/Windows%20PrivEsc%20Cheatsheet.html)

## Usage
Open any `.html` file directly in a browser — each is self-contained with no external dependencies.

## Disclaimer
This repository is for educational purposes and authorized security testing only. The author is not responsible for misuse.
