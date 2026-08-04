# 📖 Lesson Plan — Network-And-Hotspot-Safety

> **Chain L — Cybersecurity (Simulation Only)** | Staying safe on networks you don't control: public wifi risks, evil twins, TLS as the real protection, and practical habits — all explained defensively.

## What This Project Is

Get an accurate, non-alarmist picture of the risks on networks you do not control, and what genuinely protects traffic.

> **Scope:** this lesson is **defensive and simulation-only**. It builds no offensive tooling and targets no real system. Everything is practised in an isolated environment against systems I own.

## Learning Objectives

By the end I can:

1. Describe what another device on the same network can realistically observe.
2. Explain how a rogue access point impersonates a legitimate network.
3. Explain why **TLS** is the primary protection and what warnings mean.
4. Identify metadata that leaks even under encryption (DNS, SNI).
5. State where a VPN genuinely helps and where it is oversold.
6. Give correct, practical advice to non-technical people.

## Software You Will Use

- Wireshark, on your own network only.
- A test device.
- Browser developer tools.

## Build Order

1. Capture traffic on your own network; observe what is and is not readable.
2. Inspect a TLS handshake and note what remains visible.
3. Observe DNS queries in the clear; then enable encrypted DNS and compare.
4. Read a certificate warning properly and understand what it claims.
5. Write the honest risk summary for public wifi.
6. Turn it into advice a non-technical person can actually follow.

## Common Mistakes to Avoid

- Repeating the claim that public wifi exposes all your traffic — TLS changed that.
- Clicking through certificate warnings.
- Assuming a VPN solves problems it does not touch.
- Ignoring DNS and SNI leakage.
- Capturing traffic on networks you do not own.

## Check Your Understanding

The quiz covers what TLS protects, evil twins, DNS/SNI metadata, and evaluating VPN claims.

## Why This Matters (Industry Application)

Remote and hybrid work means people constantly connect from networks nobody vetted, and this is a common
security-awareness topic in any organization. Understanding what actually protects traffic — and what a VPN
does and doesn't add — makes you the person who can give colleagues correct advice.

## Reflection Questions

- What advice would you give a colleague working from a coffee shop — specifically, and without exaggeration?
- Which risk here is genuinely overstated in popular coverage, and why does that matter?
