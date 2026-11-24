<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="DynamicDNSPro Tickets" width="96">
</p>

<h1 align="center">DynamicDNSPro Tickets</h1>

<p align="center">Technical support with an agent on the machine.<br>Support tickets, live terminal, supervised AI and broadcast announcements — from the web panel or the app itself.</p>

<p align="center">
  <a href="https://tickets.dynamicdnspro.com"><img src="https://img.shields.io/badge/website-tickets.dynamicdnspro.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-tickets-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-Windows-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/dynamicdnspro-tickets-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/dynamicdnspro-tickets-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <strong>🇬🇧 English</strong> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **This repository publishes official binary releases only** — the source code is private. Signed downloads and auto-update feeds.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-tickets-releases/main/icons/windows.svg' width='15' style='vertical-align:-2px' alt='windows'> **Tickets (Windows)** | [DynamicDNSPro-Tickets-Setup.exe](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest/download/DynamicDNSPro-Tickets-Setup.exe) — always the latest stable build |
| <img src='https://dynamicdnspro.com/assets/img/logo.png' width='15' style='vertical-align:-2px'> **Website** | [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) — client portal, plans and management |

No installer needed on machines with the **DynamicDNSPro Agent**: enable Tickets on the machine (or the whole account) and the app deploys itself automatically.

## What it is

DynamicDNSPro Tickets is the support-desk module of the DynamicDNSPro ecosystem. Each client machine runs the Tickets app: users open tickets from the system tray, technicians answer from the web panel — with a live terminal on the machine, supervised AI suggestions, remote command execution and broadcast announcements to entire sites or departments.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Features

- **Tickets per machine** — end users open and follow tickets from the tray app; each ticket is bound to its machine and site.
- **Live terminal** — run cmd/PowerShell on the client machine from the panel, with user-visible output.
- **Supervised AI** — suggested replies and command assistance for technicians (Pro+).
- **Remote commands** — execute vetted commands as SYSTEM without interrupting the user (Pro+).
- **Broadcasts** — announcements to whole sites or departments with read acknowledgment.
- **Machine view** — hardware, services and status of the ticket's machine in the same screen (Basic+).
- **Knowledge base** — reusable answers and internal docs (Pro+).
- **White label** — your brand in the app (Business).
- **Roles** — technician permissions: view, attend, execute, admin.
- **Six languages** — portal and app in ES / EN / FR / IT / DE / PT.

## How to use it

1. Sign up or contract a plan at [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) (Free plan covers up to 5 machines).
2. **Machines with the Agent**: enable Tickets on the machine — the app installs itself in minutes, nothing to download.
3. **Standalone machines**: install `DynamicDNSPro-Tickets-Setup.exe` and pair it with the link token shown in *Settings* of the panel.
4. Invite your technicians, assign roles and start answering tickets — with terminal, AI and remote commands on paid plans.

## Editions & pricing

| Plan | Price | Machines | Includes |
|---|---|---|---|
| **Free** | €0 | 5 | Tickets, live terminal, broadcasts |
| **Básico** | €6/mo · €60/yr | Unlimited | Everything in Free + machine server view |
| **Pro** | €12/mo · €120/yr | Unlimited | + supervised AI, remote commands, knowledge base |
| **Business** | €24/mo · €240/yr | Unlimited | + white label (your brand in the app) |

## Requirements

Windows 10/11 x64 · Internet access to `tickets.dynamicdnspro.com` · For pairing, the link token from *Settings* (standalone installs) or the DynamicDNSPro Agent (auto-deploy).

## What's in this repository

- `DynamicDNSPro-Tickets-Setup-<version>.exe` — versioned Windows installer
- `DynamicDNSPro-Tickets-Setup.exe` — stable-name copy pointing to the latest release
- `version.json` — auto-update feed (`tickets_url` / `tickets_size`) served by the portal

[Latest release](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest)

## FAQ

**Do I need this installer on machines with the DynamicDNSPro Agent?**  
No — enable Tickets on the machine in the panel and the agent deploys the app automatically via the signed fleet channel.

**How do standalone machines link to my account?**  
After installing, the app asks for the link token shown in *Settings → Tokens* of your tickets portal.

**What does the Free plan include?**  
Tickets, live terminal and broadcasts for up to 5 machines — no card required.

## Support

- Website & client portal: [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com)
- Email: support@it-systems.es

---
<p align="center"><sub>DynamicDNSPro Tickets · © MavkSoft / IT-Systems</sub></p>
