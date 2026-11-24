<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="DynamicDNSPro Tickets" width="96">
</p>

<h1 align="center">DynamicDNSPro Tickets</h1>

<p align="center">Technischer Support mit Agent auf dem Rechner.<br>Support-Tickets, Live-Terminal, überwachte KI und Rundmeldungen — aus dem Web-Panel oder direkt aus der App.</p>

<p align="center">
  <a href="https://tickets.dynamicdnspro.com"><img src="https://img.shields.io/badge/website-tickets.dynamicdnspro.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-tickets-releases?label=neueste" alt="neueste Release"></a>
  <img src="https://img.shields.io/badge/plattform-Windows-black" alt="plattformen">
  <img src="https://img.shields.io/badge/lizenz-kommerziell-orange" alt="kommerzielle Lizenz">
</p>

<p align="center"><a href="https://mavksoft.github.io/dynamicdnspro-tickets-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/dynamicdnspro-tickets-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <strong>🇩🇪 Deutsch</strong> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Dieses Repository veröffentlicht ausschließlich offizielle Binär-Releases** — der Quellcode ist privat. Signierte Downloads und Auto-Update-Feeds.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-tickets-releases/main/icons/windows.svg' width='15' style='vertical-align:-2px' alt='windows'> **Tickets (Windows)** | [DynamicDNSPro-Tickets-Setup.exe](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest/download/DynamicDNSPro-Tickets-Setup.exe) — immer der neueste Stable-Build |
| <img src='https://dynamicdnspro.com/assets/img/logo.png' width='15' style='vertical-align:-2px'> **Website** | [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) — Kundenportal, Tarife und Verwaltung |

Auf Rechnern mit dem **DynamicDNSPro-Agent** ist kein Installer nötig: Tickets auf dem Gerät (oder für das ganze Konto) aktivieren — die App installiert sich von selbst.

## Was ist das

DynamicDNSPro Tickets ist das Support-Modul des DynamicDNSPro-Ökosystems. Auf jedem Client-Rechner läuft die Tickets-App: Nutzer öffnen Tickets aus dem Systemtray, Techniker antworten aus dem Web-Panel — mit Live-Terminal auf dem Rechner, überwachten KI-Vorschlägen, Remote-Befehlen und Rundmeldungen an ganze Standorte oder Abteilungen.

<p align="center"><img src="./screenshots/website.png" width="640" alt="Screenshot"></p>

## Funktionen

- **Tickets pro Rechner** — Nutzer öffnen und verfolgen Tickets über die Tray-App; jedes Ticket ist mit Gerät und Standort verknüpft.
- **Live-Terminal** — cmd/PowerShell auf dem Client-Rechner aus dem Panel ausführen, mit für den Nutzer sichtbarer Ausgabe.
- **Überwachte KI** — Antwortvorschläge und Befehlshilfe für Techniker (Pro+).
- **Remote-Befehle** — geprüfte Befehle als SYSTEM ausführen, ohne den Nutzer zu stören (Pro+).
- **Rundmeldungen** — Ankündigungen an ganze Standorte oder Abteilungen mit Lesebestätigung.
- **Geräteansicht** — Hardware, Dienste und Status des Ticket-Rechners auf einem Bildschirm (Básico+).
- **Wissensdatenbank** — wiederverwendbare Antworten und interne Dokumentation (Pro+).
- **White Label** — deine Marke in der App (Business).
- **Rollen** — Techniker-Rechte: ansehen, bearbeiten, ausführen, admin.
- **Sechs Sprachen** — Portal und App in ES / EN / FR / IT / DE / PT.

## So funktioniert es

1. Registrieren oder Tarif buchen auf [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) (der Gratis-Tarif deckt bis zu 5 Rechner ab).
2. **Rechner mit Agent**: Tickets auf dem Gerät aktivieren — die App installiert sich in wenigen Minuten von selbst, nichts herunterladen.
3. **Einzelne Rechner**: `DynamicDNSPro-Tickets-Setup.exe` installieren und mit dem Verknüpfungs-Token aus *Einstellungen* im Panel koppeln.
4. Techniker einladen, Rollen zuweisen und Tickets beantworten — mit Terminal, KI und Remote-Befehlen in den kostenpflichtigen Tarifen.

## Tarife & Preise

| Tarif | Preis | Rechner | Enthält |
|---|---|---|---|
| **Gratis** | 0 € | 5 | Tickets, Live-Terminal, Rundmeldungen |
| **Básico** | 6 €/Monat · 60 €/Jahr | Unbegrenzt | Alles aus Gratis + Serveransicht des Rechners |
| **Pro** | 12 €/Monat · 120 €/Jahr | Unbegrenzt | + überwachte KI, Remote-Befehle, Wissensdatenbank |
| **Business** | 24 €/Monat · 240 €/Jahr | Unbegrenzt | + White Label (deine Marke in der App) |

## Voraussetzungen

Windows 10/11 x64 · Internetzugang zu `tickets.dynamicdnspro.com` · Zum Koppeln das Verknüpfungs-Token aus *Einstellungen* (Einzelinstallationen) oder der DynamicDNSPro-Agent (Auto-Deployment).

## Inhalt dieses Repositories

- `DynamicDNSPro-Tickets-Setup-<version>.exe` — versionierter Windows-Installer
- `DynamicDNSPro-Tickets-Setup.exe` — Kopie mit stabilem Namen, die auf die neueste Release zeigt
- `version.json` — Auto-Update-Feed (`tickets_url` / `tickets_size`), vom Portal bereitgestellt

[Neueste Release](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest)

## FAQ

**Brauche ich diesen Installer auf Rechnern mit dem DynamicDNSPro-Agent?**  
Nein — Tickets im Panel auf dem Gerät aktivieren; der Agent installiert die App automatisch über den signierten Fleet-Kanal.

**Wie werden einzelne Rechner mit meinem Konto verknüpft?**  
Nach der Installation fragt die App nach dem Verknüpfungs-Token aus *Einstellungen → Tokens* deines Tickets-Portals.

**Was enthält der Gratis-Tarif?**  
Tickets, Live-Terminal und Rundmeldungen für bis zu 5 Rechner — keine Karte nötig.

## Support

- Website & Kundenportal: [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com)
- E-Mail: support@it-systems.es

---
<p align="center"><sub>DynamicDNSPro Tickets · © MavkSoft / IT-Systems</sub></p>
