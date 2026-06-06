# Sipar Security 🛡️

> Building open-source network security tools from Pakistan —
> practical, lightweight, and free for everyone.

[![Website](https://img.shields.io/badge/website-siparsecurity.github.io-00e676?style=flat&logo=google-chrome&logoColor=black)](https://siparsecurity.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sipar%20Security-0077B5?style=flat&logo=linkedin)](https://linkedin.com/company/siparsecurity)
[![X](https://img.shields.io/badge/X-@SiparSecurity-000000?style=flat&logo=x)](https://x.com/SiparSecurity)

---

## Who We Are

Sipar Security is an independent cybersecurity company from **Peshawar, Pakistan**
focused on building practical, open-source security tools that give real network
visibility to home users, IT admins, and small businesses.

We believe security should not require an enterprise budget.
Everything we build is free, open-source, and built for real use.

---

## 🔧 Projects

---

### Network Monitor v2.0 — Device Intelligence
**Latest Release · Publicly Available · Production Ready**

A Python-based SOC-grade network monitoring and intrusion detection system
with real-time device intelligence, persistent logging, and a full dark
SOC-style dashboard.
sudo python3 run_soc.py
→ Dashboard live at http://localhost:5000

**What it does:**

| Feature | Detail |
|---|---|
| Device Discovery | ARP-based scanning — MAC, IP, first seen, last seen |
| Real-Time Tracking | 7-second scan interval — online/offline status live |
| Offline Detection | DEVICE_OFFLINE after 3 consecutive missed scans |
| ARP Spoof Detection | Cooldown timer + 60s MAC randomization window |
| Persistent Logging | All events saved to JSONL — state survives restarts |
| SOC Dashboard | 5 stat cards, filtered alerts, risk color coding |
| /stats API | Top risk devices and system summary endpoint |

**→ [View Repository](https://github.com/siparsecurity/network-monitor-v2)**
**→ [Download Latest Release](https://github.com/siparsecurity/network-monitor-v2/releases)**

---

### Network Monitor v1.0 — Foundation
**First Release · Publicly Available**

The first working version of the Sipar Security Network Monitor.
ARP scan engine, event server, SOC dashboard, and auto interface detection.

**→ [View Repository](https://github.com/siparsecurity/network-monitor)**
**→ [Download v1.0](https://github.com/siparsecurity/network-monitor/releases/tag/v0.1-layer1)**

---

## 📋 Roadmap

| Version | Name | Status |
|---|---|---|
| v1.0 | Foundation | ✅ Publicly Released |
| v2.0 | Device Intelligence | ✅ Publicly Released |
| v3.0 | Alerts & Export | 🔜 In Development |

---

## 👤 Founder

**Sayed Muhammad Subayyal** — 17-year-old ethical hacker and security
researcher from Peshawar, Pakistan. Reported vulnerabilities to NASA.
Published researcher. Teaching ethical hacking with Kali Linux.

---

## 📬 Contact

| | |
|---|---|
| 🌐 Website | [siparsecurity.github.io](https://siparsecurity.github.io) |
| 📧 Email | siparsecurity@gmail.com |
| 💼 LinkedIn | [Sipar Security](https://linkedin.com/company/siparsecurity) |
| 𝕏 Twitter | [@SiparSecurity](https://x.com/SiparSecurity) |

---

*Built in Pakistan 🇵🇰 · MIT License · © 2026 Sipar Security*
