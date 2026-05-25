# 🛡️ Yanky Wilson

### 🔍 Threat Intelligence · 🎯 Attribution · 🚨 Incident Response · 🧬 Reverse Engineering

**I figure out who's behind the attack.**

When an intrusion hits, I work the artifacts — logs, memory, network telemetry, binaries, infrastructure — back to the actor. Reverse engineer the payload. Pivot the C2. TTPs to MITRE. Infrastructure to clusters. Clusters to known groups. Then I turn that intelligence into detections that catch them the next time.

---

## ⚔️ What I Do

🎯 **Attribution research** — Pivoting on infrastructure, malware, and tradecraft to link activity to known threat actors. Heavy focus on Iranian state-sponsored clusters (APT33 / Peach Sandstorm, APT42), financially motivated RMM abuse operators, and PhaaS infrastructure tracking.

🧬 **Malware reverse engineering** — Static and dynamic analysis of operator-side payloads. Identifying anti-forensic techniques, custom C2 protocols, steganographic beaconing, and configuration structures. Extracting durable signatures from binary internals that survive infrastructure rotation.

🚨 **Incident response** — Full lifecycle ownership. Triage, scoping, containment, eradication, recovery, post-incident reporting. Sole forensic investigator on complex endpoint cases including memory acquisition, browser forensics, and anti-forensic application analysis.

🔧 **Detection engineering** — Sigma, KQL, YARA, Suricata. Operationalizing IOCs and TTPs into Sentinel and Defender so the next intrusion gets caught at alert-time, not after.

🌐 **OSINT infrastructure tracking** — Censys / urlscan / passive DNS / certificate transparency pivot chains. Building cluster maps of operator infrastructure that hold up across rotation cycles.

---

## 🛠️ Stack

⚡ Microsoft Sentinel · Defender for Endpoint · CrowdStrike Falcon · Intune · Entra ID
💻 KQL · Sigma · Suricata · YARA · PowerShell · Python
🔬 Volatility · pdf-parser · pdfplumber · binary reverse engineering · Chromium DB forensics
🌐 Censys · urlscan.io · crt.sh · ANY.RUN · abuse.ch · Hunt.io · passive DNS
📊 MITRE ATT&CK · Diamond Model · Kill Chain · STIX 2.1

---

📌 Pinned Work

* 🧬 `interlock-aa25-203a-analysis` — Independent reverse engineering of CISA AA25-203A. Fifteen documented gaps between advisory and the in-the-wild Interlock encryptor; Matrix-family lineage finding; structural YARA rules; 10-phase verification methodology.
* 🐻 🇺🇦 `gamybear-cert-ua-18329-analysis` — 15+ binary-level corrections to CERT-UA#18329 GAMYBEAR. Persistence misattribution, TLS implementation failure, and IOC validation against the actual ieupdater.exe loader.
* 🎣 `sneaky2fa-kc-cluster` — OSINT analysis of an active Sneaky2FA PhaaS operator running 117 origin servers from Kansas City, MO. Documents aged-domain acquisition tradecraft for enterprise mail-filter bypass.
* 🔴 `screenconnect-rogue-tenant-investigation` — CTI and detections for rogue ScreenConnect tenant abuse
* 🌐 `DNS-Filter-Bypass-Forensics-Toolkit` — PowerShell forensics for DNS evasion on managed Windows fleets
* 🔴 🇮🇷 `iranian-apt-m365-threat-intel` — Hunts and intel on APT33 / Peach Sandstorm in M365 and Entra ID

---

## 📜 Certifications

🏅 CompTIA CySA+ · CompTIA Security+ · EC-Council Certified Threat Intelligence Analyst (C|TIA) · EC-Council Certified SOC Analyst (C|SA) · ISC2 Certified in Cybersecurity (CC)

