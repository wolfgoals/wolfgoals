# Hi, I'm Jonathan 👋
# Cloud & Security Engineering Portfolio

> Hands-on lab work targeting cloud security, cloud networking, and DevSecOps roles.

---

## Why This Portfolio Exists

Cloud security is the #1 technical skill sought by hiring managers right now, and 91% of employers prefer candidates with certifications that prove applied skills — not just credentials on paper. This portfolio is the applied layer. Every project here maps to a real job requirement, runs on real infrastructure, and produces artifacts that demonstrate judgment — not just tool familiarity.

---

## Skills Signal Map

| Where It Lives Here |
|---|---|
| Cloud security (AWS) | [AWS Site-to-Site VPN](#) · [Cert Roadmap](#) |
| Network segmentation & firewall policy | [Home Lab Network (pfSense)](#) |
| Linux administration | [Quad-Boot Workstation](#) · [NetHunter Mobile Node](#) |
| Infrastructure as Code (Terraform) | Phase 2 — in progress |
| DevSecOps / CI-CD pipeline security | Phase 2 — in progress |
| Penetration testing fundamentals | [Quad-Boot Workstation](#) · [Home Lab Network](#) |
| Zero Trust / least-privilege design | [Home Lab Network — isolated attacker/target VLANs](#) |
| Container orchestration (Kubernetes) | Phase 2 — in progress |
| Remote access & VPN architecture | [AWS Site-to-Site VPN](#) · [Tailscale mesh setup](#) |
| Self-hosted tooling without cloud dependency | [Cross-Device Study Infrastructure](#) |

---

## Active Projects

### 🔐 Home Lab Network — Isolated VM Stack
**[→ View Project](#)**

Multi-VM lab on an M1 Pro MacBook using UTM with pfSense as the network boundary. Attacker and target machines live on separate internal networks with explicit firewall rules between them. The design mirrors how enterprise environments segment red team infrastructure from production assets.

**Skills demonstrated:** Network segmentation, firewall policy, VLAN design, threat modeling, VM orchestration

**Stack:** UTM · pfSense · Kali Linux (ARM) · Metasploitable 3 · Ubuntu Server · Windows 11 ARM

---

### 🖥️ Quad-Boot Security Workstation
**[→ View Project](#)**

A 2013 MacBook Pro running four operating systems on bare metal — each selected for a specific security use case. Kali for live pentesting, Parrot OS for stable lab work, Windows 11 for modern exploit research, and Windows XP for legacy vulnerability practice. Includes an Alfa AWUS036ACH adapter configured for monitor mode and packet injection.

**Skills demonstrated:** OS-level security, legacy exploit research, wireless security tooling, multi-boot architecture

**Stack:** Kali Linux · Linux Mint · Windows 11 · Windows XP · Alfa AWUS036ACH (monitor mode)

---

### 📱 Mobile Security Node — Kali NetHunter Rootless
**[→ View Project](#)**

Kali Linux running on a Samsung Galaxy S25 without root, using NetHunter Rootless via Termux. Includes XFCE desktop via KeX/VNC, Tailscale for encrypted remote access over 5G, and a documented pivot workflow for wireless recon (the phone SSHes into the Alfa-equipped workstation rather than attempting monitor mode directly — a real engineering constraint documented honestly).

**Skills demonstrated:** Mobile security tooling, network pivoting, remote access architecture, constraint-driven design

**Stack:** Kali NetHunter Rootless · Termux (F-Droid) · Tailscale · KeX/VNC · XFCE

---

### ☁️ AWS Site-to-Site VPN — Home Lab ↔ Cloud
**[→ View Project](#)**

Connecting a local UTM-based lab to AWS over a site-to-site VPN. This is the capstone project for Phase 1 and one of the most concrete hybrid cloud skills an entry-level cloud engineer can demonstrate. Most candidates know how to click through the AWS console. Fewer can explain the IKEv2 handshake, the routing table changes on both ends, and what breaks when MTU is wrong.

**Skills demonstrated:** AWS VPC, VPN gateway configuration, BGP/static routing, hybrid cloud architecture, network troubleshooting

**Stack:** AWS VPC · Virtual Private Gateway · Customer Gateway · UTM (pfSense)

---

### 🗂️ Cross-Device Study Infrastructure
**[→ View Project](#)**

A self-hosted, peer-to-peer knowledge management system spanning three devices and two architectures. Obsidian for structured cert-mapped notes, AnkiDroid for spaced repetition, and Syncthing-Fork for zero-cloud sync. Built to eliminate the learn-forget-rediscover cycle that kills self-study momentum.

**Skills demonstrated:** Self-hosted tooling, P2P network architecture, system design for reliability, documentation discipline

**Stack:** Obsidian · Anki · Syncthing-Fork · Tailscale · Kali NetHunter Rootless

---

## Certification Roadmap

Hiring managers at the entry and junior level prioritize data security, cloud security, and risk assessment. This roadmap is sequenced to build those competencies in order, with lab work running in parallel at every phase.

| Phase | Certifications | Status |
|---|---|---|
| **Phase 1** | CompTIA Network+ · LPI Linux Essentials · AWS Cloud Practitioner | 🔄 In Progress |
| **Phase 2** | AWS Solutions Architect Associate · CompTIA Security+ · HashiCorp Terraform Associate | 📅 Planned |
| **Phase 3** | Certified Kubernetes Administrator (CKA) · AWS Security Specialty | 📅 Planned |

---

## What I'm Building Toward

The most in-demand roles in 2026 require cloud security, zero trust architecture, DevSecOps, penetration testing, and infrastructure as code. My target roles sit at the intersection of cloud engineering and security:

- **Cloud Security Engineer** — securing AWS environments, IAM hardening, CSPM
- **Cloud Network Engineer** — VPC design, hybrid connectivity, network policy
- **DevSecOps Engineer** — shifting security left in CI/CD, IaC security scanning
- **Junior Penetration Tester** — red team fundamentals grounded in real lab work

All of these roles share a common requirement: proof that you can step into a role and perform on day one. This portfolio is that proof.

---

## Technical Environment

| Category | Tools & Platforms |
|---|---|
| Cloud | AWS (VPC, VPN Gateway, EC2, IAM) |
| Virtualization | UTM (M1 Pro), bare-metal multi-boot (x86) |
| Networking | pfSense, Wireshark, Nmap, Tailscale |
| Security | Kali Linux, Metasploitable 3, Burp Suite, Alfa AWUS036ACH |
| IaC *(Phase 2)* | Terraform |
| Containers *(Phase 2)* | Docker, Kubernetes |
| OS | macOS, Kali Linux, Linux Mint, Ubuntu Server, Windows |
| Mobile | Kali NetHunter Rootless, Termux, Android |

---

## Contact

Open to cloud engineering, cloud security, and DevSecOps roles — remote preferred.

**[LinkedIn](https://www.linkedin.com/in/jonathan-harrison-ot-security-specialist/)** · **[Email](wolfiegoals11@gmail.com)**
