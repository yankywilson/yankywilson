# 🛡️ Yanky Wilson
<img width="1536" height="365" alt="hero-banner" src="https://github.com/user-attachments/assets/b81c9776-9b78-4eab-9210-110829aef04d" />
<img width="1200" height="70" alt="animated-divider" src="https://github.com/user-attachments/assets/a06ac00e-f0f1-4d1d-9de2-13ca6679e515" />
<img width="1200" height="36" alt="research-scan" src="https://github.com/user-attachments/assets/931946c2-ba0b-4aa2-b013-db26accfea08" />



<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="36" viewBox="0 0 1200 36">
<rect width="1200" height="36" fill="#050a11"/>
<path d="M0 18H1200" stroke="#12324d" stroke-width="1"/>
<path d="M0 7H1200M0 29H1200" stroke="#081a2a" stroke-width="1"/>
<circle cx="0" cy="18" r="3" fill="#1683ff">
  <animate attributeName="cx" from="0" to="1200" dur="4s" repeatCount="indefinite"/>
</circle>
<text x="600" y="23" text-anchor="middle" fill="#4aaeff"
      font-family="monospace" font-size="13" letter-spacing="4">
  
#### 🧬 Reverse Engineering · 🔍 Threat Intelligence · 🛰️ Infrastructure Analysis · 🔧 Detection Engineering

I take the malware apart and test what's been published against it.

When a campaign hits the news, I get the sample. Reverse the payload, decode the C2 protocol, walk the infrastructure — then check the vendor and CERT reporting against what the binary actually does. What holds gets confirmed. What doesn't gets corrected in public. Every investigation ships with detections, and when the crypto allows it, a working decryptor. Confidence is stated in ICD-203 language, and attribution never runs past what the evidence carries.

---

## ⚔️ What I Do

🧬 Malware reverse engineering — Static and dynamic teardown of loaders, backdoors, and ransomware in FLARE-VM and Ghidra. Recovering custom crypto schemes (misdocumented AES key formats, X25519 + XChaCha20, ChaCha20 config blobs), decoding C2 protocols, and defeating anti-analysis — down to stack-string decoys and dead-code misdirection. When the crypto allows it, the teardown ships with a working decryptor.

🔬 Verification research — Testing published vendor and CERT reporting against the actual sample. Advisory says AES-256? The binary says AES-128-CBC with the IV packed into the key. 50+ documented corrections across CISA, CERT-UA, and vendor reporting — and when a published IOC fails validation, that null result gets published too.

⛓️ On-chain C2 enumeration — Malware that stores C2 config in smart contracts leaves a permanent public record. I enumerate EtherHiding resolver contracts, replay months of C2 rotation from chain state, and anchor detections to on-chain artifacts that survive every domain burn. Coverage across MuddyWater, EtherRAT, SmartLoader, Tsundere, and DeadLock.

🌐 Infrastructure OSINT — Passive-only pivot chains through Censys (CenQL), Shodan, Validin, Hunt.io, passive DNS, and certificate transparency. Cluster maps that hold up across rotation cycles — from a 117-host PhaaS operator estate to rogue RMM tenants. Operator assets are never touched.

🔧 Detection engineering — YARA, Sigma, Suricata, KQL, SPL. Every investigation ends as deployable content for Sentinel and Defender, organized to ATT&CK, with false-positive sources and tuning notes documented — so the next intrusion gets caught at alert-time, not after.

---

## 🛠️ Stack

🔬 Reverse engineering — Ghidra · FLARE-VM · x64dbg · Detect It Easy · FLOSS · pefile / capstone · Volatility

📡 Network & sandbox — Wireshark  · ANY.RUN · Triage · Joe Sandbox · VirusTotal

🌐 Infrastructure OSINT — Censys (CenQL) · Shodan · Validin · Hunt.io (HuntSQL) · Silent Push · urlscan.io · crt.sh · passive DNS

⛓️ On-chain analysis — smart-contract enumeration · event-log replay · C2 rotation reconstruction from chain state

🔧 Detection & standards — YARA · Sigma · Suricata · KQL · SPL · STIX 2.1

⚡ Operations — Microsoft Sentinel · Defender XDR · CrowdStrike Falcon · Entra ID · Intune

💻 Languages — Python (decryptors, tooling) · PowerShell · Go (RE target)

📊 Frameworks — MITRE ATT&CK · Diamond Model · Kill Chain · ICD-203

---

### 📌 The Work
🔬 I reverse engineer malware from active campaigns and publish the full teardowns in the repos below

🧾 Where the analysis extends or corrects public reporting, each finding is documented in-repo — 15 findings on CERT-UA#18329, 10 on CISA AA26-097A, 25+ gaps on CISA AA25-050A

⛓️ I track malware that hosts C2 in smart contracts — resolver contracts and rotation history recovered from chain state across six families

🔧 Every investigation ships detection content — YARA, Sigma, Suricata, KQL — and structured, ATT&CK-mapped IOCs

🔓 Decryptors included when the crypto allows — tested with round-trip validation

📊 Assessments use ICD-203 estimative language; corrections live in a public retraction log

✍️ Some of this research runs at CSO Online and on my blog

🆕 New investigations land regularly — the pinned repos carry the current flagship work

---

## 📜 Certifications

🏅 CompTIA CySA+ · CompTIA Security+ · EC-Council Certified Threat Intelligence Analyst (C|TIA) · EC-Council Certified SOC Analyst (C|SA) · ISC2 Certified in Cybersecurity (CC)

