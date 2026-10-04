<div align="center">

# Hi, I'm Ubong Udofia 👋

**Cybersecurity GRC | IT Audit | SOC | Threat Intelligence | Penetration Testing**

📍 Kamloops, BC, Canada

![Profile Views](https://komarev.com/ghpvc/?username=UbongUdofia84&color=blueviolet&style=flat-square)
![GitHub followers](https://img.shields.io/github/followers/UbongUdofia84?label=Follow&style=social)

</div>

---

## 🛡️ About Me

I’m a cybersecurity and GRC professional with experience in IT Audit, Governance, Risk & Compliance (GRC), risk assessment, control evaluation, audit support, and remediation tracking, supported by a background in Project Management (PMP) and engineering.
Alongside my professional GRC work, I’m continuing to build hands-on technical depth through structured labs and simulated engagements across several areas:
• 🧪 Penetration Testing — full-lifecycle VAPT engagements, from Rules of Engagement through technical assessment and client-ready reporting
• 🚨 Security Operations (SOC) — detection, triage, and incident investigation using SIEM, firewall, authentication, and network telemetry
• 🔭 Threat Intelligence — threat actor profiling, TTP analysis, MITRE ATT&CK mapping, and risk assessment
• 🌐 Networking & Security Fundamentals — Linux system/network diagnostics, routing, ARP/ICMP, firewall configuration, and traffic analysis
These projects help me connect governance and control requirements with the technical security events, vulnerabilities, and attack paths those controls are designed to address.
Every project below is a hands-on lab I have completed end-to-end, documented, and can walk through in an interview.

---

## 🧰 Tools & Technologies

**Reconnaissance & OSINT**

![Nmap](https://img.shields.io/badge/Nmap-000000?style=for-the-badge&logo=nmap&logoColor=white)
![OSINT](https://img.shields.io/badge/OSINT-1E3A5F?style=for-the-badge)
![Google Dorking](https://img.shields.io/badge/Google%20Dorking-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Gobuster](https://img.shields.io/badge/Gobuster-2E8B57?style=for-the-badge)
![WhatWeb](https://img.shields.io/badge/WhatWeb-4B0082?style=for-the-badge)

**Vulnerability Assessment & Exploitation**

![Nessus](https://img.shields.io/badge/Nessus-00A0E3?style=for-the-badge)
![Nikto](https://img.shields.io/badge/Nikto-800000?style=for-the-badge)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge)
![SQLMap](https://img.shields.io/badge/SQLMap-D22128?style=for-the-badge)
![OWASP](https://img.shields.io/badge/OWASP%20Top%2010-000000?style=for-the-badge&logo=owasp&logoColor=white)

**SOC, Monitoring & Network Defense**

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3AB595?style=for-the-badge)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=for-the-badge)
![SIEM](https://img.shields.io/badge/SIEM-333333?style=for-the-badge)

**Threat Intelligence & Risk Frameworks**

![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=for-the-badge)
![NIST CSF](https://img.shields.io/badge/NIST%20CSF-1E3A5F?style=for-the-badge)
![Risk Assessment](https://img.shields.io/badge/Risk%20Assessment-4B4B4B?style=for-the-badge)

**Networking Fundamentals**

![Cisco Packet Tracer](https://img.shields.io/badge/Cisco%20Packet%20Tracer-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Cisco IOS](https://img.shields.io/badge/Cisco%20IOS-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![ARP](https://img.shields.io/badge/ARP-4B4B4B?style=for-the-badge)
![ICMP](https://img.shields.io/badge/ICMP-4B4B4B?style=for-the-badge)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-333333?style=for-the-badge)

**Platforms & GRC**

![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
![PMP](https://img.shields.io/badge/PMP%20Certified-00A651?style=for-the-badge)
![GRC](https://img.shields.io/badge/GRC%20%2F%20IT%20Audit-003366?style=for-the-badge)

---

## 🎯 Featured Projects

### 🔓 [VAPT Capstone — Simulated Fintech Payment Platform](./vapt-capstone-kassera-pay)
Full-lifecycle penetration test against a simulated payments platform (Metasploitable 2 + DVWA), run as a real paid engagement would be: scoping and RoE, recon, vulnerability assessment, exploitation, web app testing, and a client-ready report.
- 9/9 targeted network services exploited or validated; 8 yielded full root access
- SQL injection used to fully extract and crack the web app's user credential store
- Findings mapped to CVSS v3.1, OWASP Top 10, and business impact (PCI DSS, data protection law)

`Nmap` `Nessus` `Nikto` `Metasploit` `SQLMap` `OWASP Top 10`

### 🚨 [SOC Incident Investigation — SSH Brute-Force Detection](./soc-incident-ssh-bruteforce)
Detected, investigated, and contained a simulated multi-stage attack (recon → port scan → SSH brute force) against a segmented lab network using firewall and endpoint telemetry.
- Correlated evidence across Wireshark, pfSense firewall logs, and Wazuh SIEM alerts
- Mapped attacker behaviour to MITRE ATT&CK (T1110.001, T1110, T1021.004)
- Built and validated a pfSense containment rule, then delivered a 9-point prioritized hardening plan

`Wireshark` `pfSense` `Wazuh` `MITRE ATT&CK` `Incident Response`

### 🕵️ [Threat Actor Profiling & Risk Assessment — Fintech Sector](./threat-actor-profiling-fintech)
A threat intelligence capstone profiling five financially motivated threat groups (Scattered Spider, LockBit, ALPHV/BlackCat, FIN7, Lazarus Group) against a hypothetical fintech's attack surface.
- Applied the full threat intelligence lifecycle: planning, OSINT collection, processing, analysis, dissemination
- Ranked and selected the most relevant actor (Scattered Spider) with a supporting real-world case study (MGM Resorts / Caesars, 2023)
- Delivered a risk matrix, NIST CSF control mapping, and an incident response playbook for identity-compromise scenarios

`MITRE ATT&CK` `NIST CSF` `OSINT` `Risk Matrix` `Threat Modeling`

### 🐧 [Linux & Networking Fundamentals Lab](./linux-networking-fundamentals)
Foundational command-line and networking diagnostics lab — system enumeration, resource auditing, and connectivity testing on Kali Linux.
- System and hardware enumeration (`uname`, `lscpu`, `free`, `df`, `uptime`)
- Connectivity and latency testing (`ping`) against both IP and DNS-resolved targets
- Documented and interpreted every result rather than just running commands

`Linux CLI` `Networking Basics` `Kali Linux`

### 📡 [Cisco Networking Fundamentals — ARP, ICMP & Router Configuration](./cisco-networking-fundamentals)
Cisco Packet Tracer labs covering core Layer 2/3 protocol behaviour and foundational router configuration.
- Traced the full ARP resolution flow — broadcast request, unicast reply, cache update — and its relevance to ARP spoofing risk
- Tested and interpreted ICMP Echo Request/Reply, Destination Unreachable, and Time Exceeded behaviour
- Practiced Cisco IOS configuration: interface addressing, hostnames, and securing console/VTY/privileged access

`Cisco Packet Tracer` `Cisco IOS` `ARP` `ICMP` `Routing & Switching`

---

## 📚 Currently Learning

- Security Operations Center (SOC) detection engineering and alert-tuning workflows
- Cloud security fundamentals (AWS/Azure security services)
- Active Directory attack paths and privilege escalation techniques

---


</div>

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/ubong-g-udofia)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](ubonggregory@gmail.com)



---

<div align="center">
<sub>🛡️ Always testing within scope, always documenting the evidence.</sub>
</div>

