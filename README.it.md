<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="DynamicDNSPro Tickets" width="96">
</p>

<h1 align="center">DynamicDNSPro Tickets</h1>

<p align="center">Supporto tecnico con un agente sulla macchina.<br>Ticket di assistenza, terminale live, IA supervisionata e annunci — dal pannello web o dalla stessa app.</p>

<p align="center">
  <a href="https://tickets.dynamicdnspro.com"><img src="https://img.shields.io/badge/sito-tickets.dynamicdnspro.com-0A84FF" alt="sito"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-tickets-releases?label=ultima" alt="ultima release"></a>
  <img src="https://img.shields.io/badge/piattaforma-Windows-black" alt="piattaforme">
  <img src="https://img.shields.io/badge/licenza-commerciale-orange" alt="licenza commerciale">
</p>

<p align="center"><a href="https://mavksoft.github.io/dynamicdnspro-tickets-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/dynamicdnspro-tickets-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <strong>🇮🇹 Italiano</strong> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Questo repository pubblica solo release binarie ufficiali** — il codice sorgente è privato. Download firmati e feed di auto-aggiornamento.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-tickets-releases/main/icons/windows.svg' width='15' style='vertical-align:-2px' alt='windows'> **Tickets (Windows)** | [DynamicDNSPro-Tickets-Setup.exe](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest/download/DynamicDNSPro-Tickets-Setup.exe) — sempre l'ultima build stabile |
| <img src='https://dynamicdnspro.com/assets/img/logo.png' width='15' style='vertical-align:-2px'> **Sito web** | [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) — portale clienti, piani e gestione |

Sulle macchine con l'**Agente DynamicDNSPro** non serve l'installer: attiva Tickets sulla macchina (o su tutto l'account) e l'app si distribuisce da sola.

## Cos'è

DynamicDNSPro Tickets è il modulo di supporto tecnico dell'ecosistema DynamicDNSPro. Ogni macchina cliente esegue l'app Tickets: gli utenti aprono ticket dalla tray di sistema e i tecnici rispondono dal pannello web — con terminale live sulla macchina, suggerimenti di IA supervisionata, esecuzione remota di comandi e annunci verso intere sedi o reparti.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funzionalità

- **Ticket per macchina** — gli utenti aprono e seguono i ticket dall'app nella tray; ogni ticket è legato alla sua macchina e alla sua sede.
- **Terminale live** — esegui cmd/PowerShell sulla macchina cliente dal pannello, con output visibile all'utente.
- **IA supervisionata** — risposte suggerite e assistenza sui comandi per i tecnici (Pro+).
- **Comandi remoti** — esegui comandi verificati come SYSTEM senza interrompere l'utente (Pro+).
- **Annunci** — comunicazioni verso intere sedi o reparti con conferma di lettura.
- **Vista macchina** — hardware, servizi e stato della macchina del ticket nella stessa schermata (Básico+).
- **Knowledge base** — risposte riutilizzabili e documentazione interna (Pro+).
- **White label** — il tuo marchio nell'app (Business).
- **Ruoli** — permessi dei tecnici: visualizza, gestisci, esegui, admin.
- **Sei lingue** — portale e app in ES / EN / FR / IT / DE / PT.

## Come si usa

1. Registrati o sottoscrivi un piano su [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) (il piano Gratis copre fino a 5 macchine).
2. **Macchine con l'Agente**: attiva Tickets sulla macchina — l'app si installa da sola in pochi minuti, niente da scaricare.
3. **Macchine singole**: installa `DynamicDNSPro-Tickets-Setup.exe` e abbinala con il token di collegamento mostrato in *Impostazioni* del pannello.
4. Invita i tuoi tecnici, assegna i ruoli e inizia a rispondere ai ticket — con terminale, IA e comandi remoti nei piani a pagamento.

## Edizioni e prezzi

| Piano | Prezzo | Macchine | Include |
|---|---|---|---|
| **Gratis** | 0 € | 5 | Ticket, terminale live, annunci |
| **Básico** | 6 €/mese · 60 €/anno | Illimitate | Tutto Gratis + vista server della macchina |
| **Pro** | 12 €/mese · 120 €/anno | Illimitate | + IA supervisionata, comandi remoti, knowledge base |
| **Business** | 24 €/mese · 240 €/anno | Illimitate | + white label (il tuo marchio nell'app) |

## Requisiti

Windows 10/11 x64 · Accesso a Internet verso `tickets.dynamicdnspro.com` · Per l'abbinamento, il token di collegamento da *Impostazioni* (installazioni singole) oppure l'Agente DynamicDNSPro (distribuzione automatica).

## Contenuto di questo repository

- `DynamicDNSPro-Tickets-Setup-<versione>.exe` — installer Windows versionato
- `DynamicDNSPro-Tickets-Setup.exe` — copia con nome stabile che punta all'ultima release
- `version.json` — feed di auto-aggiornamento (`tickets_url` / `tickets_size`) servito dal portale

[Ultima release](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest)

## FAQ

**Mi serve questo installer sulle macchine con l'Agente DynamicDNSPro?**  
No — attiva Tickets sulla macchina nel pannello e l'agente distribuisce l'app automaticamente tramite il canale fleet firmato.

**Come si collegano le macchine singole al mio account?**  
Dopo l'installazione, l'app chiede il token di collegamento mostrato in *Impostazioni → Token* del tuo portale tickets.

**Cosa include il piano Gratis?**  
Ticket, terminale live e annunci fino a 5 macchine — senza carta.

## Supporto

- Sito e portale clienti: [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com)
- Email: support@it-systems.es

---
<p align="center"><sub>DynamicDNSPro Tickets · © MavkSoft / IT-Systems</sub></p>
