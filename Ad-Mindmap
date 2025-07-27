# Active Directory Mindmap 2025

This repository contains a Markdown version of the Active Directory Attack & Defense Mindmap (2025).

It helps red teamers, blue teamers, and SOC analysts understand AD security concepts from initial access to persistence and evasion. Inspired by real-world attack chains, the mindmap also serves as a structured learning and planning tool.

---

## Table of Contents

- [Initial Access](#initial-access)
- [Account Discovery](#account-discovery)
- [Credential Access](#credential-access)
- [Privilege Escalation](#privilege-escalation)
- [Lateral Movement](#lateral-movement)
- [Persistence](#persistence)
- [Defense Evasion](#defense-evasion)
- [Domain Understanding and Recon](#domain-understanding-and-recon)
- [How This Was Generated](#how-this-was-generated)
- [Source and License](#source-and-license)

---

## Initial Access

- Phishing (spear-phishing attachments or links)
- Exploiting exposed services (RDP, VPN, web portals)
- Active Directory Certificate Services (AD CS) abuse
- SCCM / MECM abuse

---

## Account Discovery

- LDAP queries and PowerShell-based user/group enumeration
- Extracting SPNs for Kerberoasting
- Using tools like BloodHound, ADFind, or PowerView

---

## Credential Access

- Kerberoasting via TGS requests
- Brute force and password spraying
- DCSync attacks
- LSASS memory dumping (Mimikatz, ProcDump, Dumpert)
- NTDS.dit and backup file extraction

---

## Privilege Escalation

- Abusing ACLs on AdminSDHolder or OU objects
- Group Policy Object (GPO) misconfiguration
- Exploiting trust relationships between domains
- AD CS privilege escalation paths

---

## Lateral Movement

- WMI execution and PowerShell remoting
- PsExec, WMIC, remote tasks
- Pass-the-Hash and Pass-the-Ticket
- Remote service creation and code execution

---

## Persistence

- Golden Ticket attacks
- Skeleton Key malware
- Backdoor service accounts
- Scheduled tasks with elevated rights

---

## Defense Evasion

- Clearing or modifying security logs
- Disabling or bypassing auditing and logging
- SIDHistory injection
- Hiding users, groups, or C2 traffic

---

## Domain Understanding and Recon

- Enumerating sites and replication topology
- Identifying trust relationships
- Gathering Global Catalog and DNS records
- Enumerating FSMO roles and domain controller details

---

## How This Was Generated

This mindmap was created by Orange Cyberdefense and converted into Markdown for version-controlled documentation.

- Written in Markdown
- Rendered using Excalidraw
- Exported as SVG

Pull requests and contributions are welcome.

---

## Source and License

- Original Mindmap (SVG):  
  https://orange-cyberdefense.github.io/ocd-mindmaps/img/mindmap_ad_dark_classic_2025.03.excalidraw.svg

- Project Repository:  
  https://github.com/Orange-Cyberdefense/ocd-mindmaps
