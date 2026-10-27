
# Penetration Testing & Offensive Security

## Jump to a Phase

- [01 — Reconnaissance & OSINT](#01--reconnaissance--osint)
- [02 — Network & Service Enumeration](#02--network--service-enumeration)
- [03 — Web & API Enumeration](#03--web--api-enumeration)
- [04 — Active Directory Enumeration](#04--active-directory-enumeration)
- [05 — Vulnerability Analysis](#05--vulnerability-analysis)
- [06 — Exploitation & Initial Access](#06--exploitation--initial-access)
- [07 — Privilege Escalation: Windows](#07--privilege-escalation-windows)
- [07 — Privilege Escalation: Linux](#07--privilege-escalation-linux)
- [08 — Post-Exploitation](#08--post-exploitation)
- [09 — Lateral Movement](#09--lateral-movement)
- [10 — Persistence & Defense Evasion](#10--persistence--defense-evasion)

---

## 01 — Reconnaissance & OSINT

| Resource | Type | Purpose |
|---|---|---|
| [OWASP Amass](https://github.com/owasp-amass/amass) | Tool | External asset discovery and attack-surface mapping. |
| [Subfinder](https://github.com/projectdiscovery/subfinder) | Tool | Passive subdomain enumeration. |
| [httpx](https://github.com/projectdiscovery/httpx) | Tool | HTTP probing and service fingerprinting. |
| [theHarvester](https://github.com/laramies/theHarvester) | Tool | Public-source domain and infrastructure reconnaissance. |

## 02 — Network & Service Enumeration

| Resource | Type | Purpose |
|---|---|---|
| [Nmap](https://nmap.org/) | Tool | Host discovery, port scanning, and service identification. |
| [Nmap Reference Guide](https://nmap.org/book/man.html) | Official reference | Command-line options, NSE, and scanning behavior. |
| [Wireshark](https://www.wireshark.org/) | Tool | Packet capture and protocol inspection. |
| [Impacket](https://github.com/fortra/impacket) | Toolkit | SMB, RPC, Kerberos, and other protocol utilities. |
| [Masscan](https://github.com/robertdavidgraham/masscan) | Tool | High-speed TCP port discovery; review maintenance before use. |

## 03 — Web & API Enumeration

| Resource | Type | Purpose |
|---|---|---|
| [Burp Suite](https://portswigger.net/burp) | Tool | Intercept and inspect web application traffic. |
| [ffuf](https://github.com/ffuf/ffuf) | Tool | Web path, host, and parameter fuzzing. |
| [Katana](https://github.com/projectdiscovery/katana) | Tool | Web crawling and endpoint discovery. |
| [OWASP ZAP](https://www.zaproxy.org/) | Tool | Web application scanning and traffic analysis. |
| [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) | Cheat sheets | Continuously developed web and API security references. |

## 04 — Active Directory Enumeration

| Resource | Type | Purpose |
|---|---|---|
| [BloodHound](https://bloodhound.specterops.io/) | Tool | Identity relationships and attack-path analysis. |
| [Active Directory PowerShell](https://learn.microsoft.com/en-us/powershell/module/activedirectory/) | Official reference | Directory querying and administration cmdlets. |
| [PowerUpSQL](https://github.com/NetSPI/PowerUpSQL) | Tool | SQL Server discovery and assessment; verify recent maintenance. |

## 05 — Vulnerability Analysis

| Resource | Type | Purpose |
|---|---|---|
| [Nuclei](https://github.com/projectdiscovery/nuclei) | Tool | Template-based security checks. |
| [Nuclei Templates](https://github.com/projectdiscovery/nuclei-templates) | Maintained templates | Checks for newly disclosed vulnerabilities and misconfigurations. |
| [Nessus](https://www.tenable.com/products/nessus) | Tool | Network vulnerability assessment. |
| [Greenbone](https://www.greenbone.net/) | Tool | Vulnerability scanning and management. |
| [CISA KEV Catalog](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) | Living reference | Known vulnerabilities exploited in the wild. |

## 06 — Exploitation & Initial Access

| Resource | Type | Purpose |
|---|---|---|
| [Metasploit Framework](https://www.metasploit.com/) | Tool | Controlled exploitation and validation. |
| [Metasploit Documentation](https://docs.metasploit.com/) | Official reference | Framework modules and workflows. |
| [sqlmap](https://sqlmap.org/) | Tool | SQL injection detection and validation. |
| [Gophish](https://getgophish.com/) | Open-source phishing simulation framework for email creation, campaign delivery, landing pages, and engagement tracking. |
| [PhishingBox](https://www.phishingbox.com/) | Phishing campaign management, customizable templates, and reporting. |
| [Lovable](https://lovable.dev/) | AI-powered web application development platform for building custom phishing simulation landing pages and web interfaces. |

## 07 — Privilege Escalation: Windows

| Resource | Type | Purpose |
|---|---|---|
| [WinPEAS (PEASS-ng)](https://github.com/peass-ng/PEASS-ng) | Tool | Windows local privilege-escalation enumeration. |
| [Microsoft Sysinternals](https://learn.microsoft.com/en-us/sysinternals/) | Toolkit | Process, service, permission, and system inspection. |
| [HackTricks — Windows Privilege Escalation](https://book.hacktricks.wiki/en/windows-hardening/windows-local-privilege-escalation/index.html) | Living cheat sheet | Windows escalation checks and techniques. |

## 07 — Privilege Escalation: Linux

| Resource | Type | Purpose |
|---|---|---|
| [LinPEAS (PEASS-ng)](https://github.com/peass-ng/PEASS-ng) | Tool | Linux local privilege-escalation enumeration. |
| [Linux Exploit Suggester](https://github.com/The-Z-Labs/linux-exploit-suggester) | Tool | Potential kernel-related escalation exposure; verify recent maintenance. |
| [HackTricks — Linux Privilege Escalation](https://book.hacktricks.wiki/en/linux-hardening/privilege-escalation/index.html) | Living cheat sheet | Linux privilege-escalation checks and techniques. |

## 08 — Post-Exploitation

| Resource | Type | Purpose |
|---|---|---|
| [Impacket](https://github.com/fortra/impacket) | Toolkit | Authenticated Windows and network protocol operations. |
| [Microsoft Sysinternals](https://learn.microsoft.com/en-us/sysinternals/) | Toolkit | Local system, process, and persistence inspection. |
| [MITRE ATT&CK — Discovery](https://attack.mitre.org/tactics/TA0007/) | Living reference | Post-access discovery techniques. |

## 09 — Lateral Movement

| Resource | Type | Purpose |
|---|---|---|
| [BloodHound](https://bloodhound.specterops.io/) | Tool | Identity-based movement and privilege path analysis. |
| [Impacket](https://github.com/fortra/impacket) | Toolkit | Remote authentication and protocol assessment. |
| [MITRE ATT&CK — Lateral Movement](https://attack.mitre.org/tactics/TA0008/) | Living reference | Lateral movement technique catalog. |

## 10 — Persistence & Defense Evasion

| Resource | Type | Purpose |
|---|---|---|
| [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) | Toolkit | Controlled adversary-technique and detection validation. |
| [Autoruns](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns) | Tool | Windows autostart and persistence inspection. |
| [MITRE ATT&CK — Persistence](https://attack.mitre.org/tactics/TA0003/) | Living reference | Persistence technique catalog. |
| [MITRE ATT&CK — Defense Evasion](https://attack.mitre.org/tactics/TA0005/) | Living reference | Defense-evasion technique catalog. |

