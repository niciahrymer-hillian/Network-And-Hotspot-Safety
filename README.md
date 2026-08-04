# Network-And-Hotspot-Safety

### Staying safe on networks you don't control: public wifi risks, evil twins, TLS as the real protection, and practical habits — all explained defensively.

![Chain L](https://img.shields.io/badge/Chain%20L-DC2626?style=for-the-badge) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)](LICENSE-GPL) [![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue?style=for-the-badge)](LICENSE-AGPL)

[📖 Lesson Plan](docs/LESSON_PLAN.md) · [🎮 Interactive Tour](docs/interactive/index.html)

<!-- SCREENSHOT PLACEHOLDER: docs/screenshots/overview.png -->

> ⬜ **Scaffold pending.** Directory created to portfolio standard; full content (README, lesson plan, tour + quiz, skeleton code) still to be built. Part of **Chain L — Cybersecurity (Simulation Only)**.

## Why This Was Built

Public wifi is surrounded by both genuine risk and a lot of fear-mongering. The honest picture is more
useful than either: TLS protects the contents of your traffic almost everywhere now, but network metadata,
captive portals, and convincing fake access points are still real problems.

I want to be able to explain accurately what someone on the same network can and can't see, because that's
practically useful to the non-technical people around me — and because getting it right matters more than
sounding alarming.

## Why This Matters (Industry Application)

Remote and hybrid work means people constantly connect from networks nobody vetted, and this is a common
security-awareness topic in any organization. Understanding what actually protects traffic — and what a VPN
does and doesn't add — makes you the person who can give colleagues correct advice.

## Topics Covered

| Area | What this project covers |
|------|--------------------------|
| Public wifi | What another device on the network can realistically observe |
| Evil twins | Rogue access points impersonating a legitimate network |
| TLS | Why HTTPS is the main protection, and what certificate warnings mean |
| Metadata | What leaks even when contents are encrypted (DNS, SNI) |
| VPN role | Where a VPN genuinely helps and where it's oversold |
| Habits | Practical, non-paranoid defensive behaviour |

## How This Connects

Chain L (Cybersecurity — Simulation Only). Pairs with **VPN-Deep-Dive-And-Simulator** and **Home-Networking-And-Firewalls** in Chain K.

---
Dual licensed — [GPL v3](LICENSE-GPL) and [AGPL v3](LICENSE-AGPL).
