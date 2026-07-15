<div align="center">

# Muhammad Harith Muanis Bin Masrur

**Cybersecurity Graduate · CompTIA Security+ · Immediately Available**

[![Email](https://img.shields.io/badge/harith-grey?style=flat-square&logo=gmail)](mailto:muhammadharithmuanismasrur@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-grey?style=flat-square&logo=linkedin)](https://linkedin.com)
[![Malaysia](https://img.shields.io/badge/Nilai%2C%20Malaysia-grey?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

I'm a final-year Computer Science student at USIM majoring in Information Security & Assurance, graduating August 2026. My internship at NetByteSec was where things got real — I deployed a live honeypot, watched actual attackers hit it, and dug through 1.1 million Splunk events to figure out what they were doing.

Outside of internship work I compete in national CTFs, build my own lab environments, and have been working on a purple team exercise where I set up a server from scratch and run both sides of the attack — offensive ops followed by detection and response against my own infrastructure.

---

## Education

| | | |
|---|---|---|
| B.Sc. (Hons) Computer Science — Information Security & Assurance | USIM | CGPA 3.67 · Dean's Award ×4 (incl. 4.00 final sem) |
| Foundation in Engineering | UiTM | CGPA 3.93 · Dean's Award ×2 |

---

## Certifications

| | | |
|---|---|---|
| Wireless Penetration Tester | 0Day Academy | Feb 2026 |
| CompTIA Security+ | CompTIA | Jan 2026 |
| Blue Team Junior Analyst | CENTRI | — |
| CCoE Career in Cybersecurity (Entry) | BlackBerry | May 2025 |
| Introduction to Cloud Computing | — | May 2025 |
| Introduction to Cryptography | — | Nov 2024 |
| Certified Artificial Intelligence (CAI) | — | In Progress |

**Courses & training:** CompTIA Security+, CompTIA Pentest+, Cloud Computing (BlackBerry CCoE) · Drone Simulation & Flying (AKSADRONE)

---

## CTF & Competitions

| | | |
|---|---|---|
| 🥈 Silver Medal — ShadowNet (5th Innovation Bank Challenge, Negeri Sembilan FOI) | 2025 | National |
| LigaCTF — Top 4, Week 6 (web, crypto, forensics, OSINT, RE) | 2026 | National |
| HackNyx (web, crypto, forensics, OSINT) | 2026 | National |
| Hack@10 (web, crypto, forensics, OSINT) | 2026 | National |
| Top 6% — Bahtera Siber CTF 3108 | 2025 | National |
| ACOTECH Hackathon | 2025 | National |
| CTF Wargames MY | 2024 | National |

---

## Skills

**Blue Team / SOC**
SIEM log ingestion & correlation · SPL querying · incident timeline reconstruction · alert tuning

**Digital Forensics**
Disk image acquisition (VMDK) · PCAP analysis · Windows persistence artefacts (Credential Manager, registry, scheduled tasks)

**Red Team / Offensive**
Vulnerability assessment · phishing simulation · web exploitation · wireless pentesting

**Purple Team**
Lab infrastructure setup from scratch · adversary emulation · detection validation · gap analysis

**Threat Intelligence**
Honeypot deployment · attacker tradecraft profiling · investigation playbook development

**Machine Learning & AI**
YOLO (computer vision) · WEKA (data mining)

**Programming**
Advanced: PHP, HTML, C, C++ · Intermediate: Java, Python, Arduino

---

## Tools

![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-004170?style=flat-square&logo=nmap&logoColor=white)
![Nessus](https://img.shields.io/badge/Nessus-00B4C8?style=flat-square&logo=tenable&logoColor=white)
![GoPhish](https://img.shields.io/badge/GoPhish-00A896?style=flat-square&logo=go&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Autopsy](https://img.shields.io/badge/Autopsy-4B4B4B?style=flat-square&logo=files&logoColor=white)
![FTK Imager](https://img.shields.io/badge/FTK_Imager-6D3B8E?style=flat-square&logo=files&logoColor=white)
![Auditd](https://img.shields.io/badge/Auditd-EE0000?style=flat-square&logo=linux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

## Projects

### 🍯 Honeypot Deployment & Threat Analysis
**NetByteSec Internship · March 2025 – August 2026**

Set up a Drupal 10 honeypot on Proxmox dressed up as a plausible Malaysian corporate environment — fake staff accounts, honeytoken credentials, canary tokens. The goal was to attract real attacker activity and observe what they actually do once they're in.

Ended up with ~1.1 million events across six Splunk sourcetypes. Wrote a custom investigation playbook and a full incident report off the back of it, which surfaced two separate attacker IPs with noticeably different tradecraft. Built the whole stack myself: Nginx, Auditd, Splunk Universal Forwarder, and network monitoring.

---

### 🔴🔵 Purple Team Exercise — Self-Hosted Lab
**In Progress**

Spinning up a server from scratch as a target environment, then running both sides against it. Red team phase covers the usual: recon, exploitation, lateral movement. Blue team phase is about building the detection side — log collection, SIEM alerts, and incident write-ups — to see what actually gets caught and what slips through.

The point isn't just to attack or just to defend. It's to close the loop and understand where the gaps are between what an attacker does and what the defender sees.

---

### 🔍 Disk & Network Forensics
**NetByteSec Internship · March 2025 – August 2026**

Forensic acquisition and analysis of a Windows VMDK using FTK Imager and Autopsy — pulled filesystem artefacts, credential stores, and attacker footprints out of the image. Also worked through a 314 MB packet capture in Wireshark tracing a time-based blind SQL injection (`pg_sleep` via `forgotpassword.php`) back to the exfiltrated credentials. Finished by ingesting everything into Splunk and rebuilding the attack timeline with SPL queries.

---

### 🔐 ShadowNet — Secure Data Transfer Framework
**October 2025 · 🥈 Silver Medal, 5th Innovation Bank Challenge**

A secure file transfer mechanism built around steganography combined with quantum-resistant encryption. Presented as main pitcher, placed above 116+ teams at the Negeri Sembilan Festival of Ideas.

---

### 🚁 Anti-Drone Detection System
**Final Year Project · Feb 2025 – Jan 2026**

Trained a YOLO-based computer vision model to flag unauthorised drones inside a defined surveillance boundary. Handled everything from dataset prep through to real-time video inference.

---

### 🎣 Phishing Simulation — Ethical Hacking Exercise
**July 2024**

Ran a controlled phishing campaign using GoPhish against a simulated organisation, tracked who clicked what, then delivered awareness briefings based on the results.
📹 [Video demo](https://youtu.be/Gyld9TD0LeE)

---

<div align="center">
<sub>Open to roles in SOC, threat intelligence, digital forensics, and penetration testing</sub>
</div>
