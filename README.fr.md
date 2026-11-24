<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="DynamicDNSPro Tickets" width="96">
</p>

<h1 align="center">DynamicDNSPro Tickets</h1>

<p align="center">Support technique avec un agent sur la machine.<br>Tickets d'assistance, terminal en direct, IA supervisée et annonces — depuis le panneau web ou l'application elle-même.</p>

<p align="center">
  <a href="https://tickets.dynamicdnspro.com"><img src="https://img.shields.io/badge/site-tickets.dynamicdnspro.com-0A84FF" alt="site"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-tickets-releases?label=dernière" alt="dernière release"></a>
  <img src="https://img.shields.io/badge/plateforme-Windows-black" alt="plateformes">
  <img src="https://img.shields.io/badge/licence-commerciale-orange" alt="licence commerciale">
</p>

<p align="center"><a href="https://mavksoft.github.io/dynamicdnspro-tickets-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/dynamicdnspro-tickets-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <strong>🇫🇷 Français</strong> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Ce dépôt ne publie que des releases binaires officielles** — le code source est privé. Téléchargements signés et flux de mise à jour automatique.

## Téléchargement

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-tickets-releases/main/icons/windows.svg' width='15' style='vertical-align:-2px' alt='windows'> **Tickets (Windows)** | [DynamicDNSPro-Tickets-Setup.exe](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest/download/DynamicDNSPro-Tickets-Setup.exe) — toujours la dernière version stable |
| <img src='https://dynamicdnspro.com/assets/img/logo.png' width='15' style='vertical-align:-2px'> **Site web** | [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) — portail client, offres et gestion |

Sur les machines équipées de l'**Agent DynamicDNSPro**, aucun installateur n'est nécessaire : activez Tickets sur la machine (ou sur tout le compte) et l'application se déploie toute seule.

## Qu'est-ce que c'est

DynamicDNSPro Tickets est le module de support technique de l'écosystème DynamicDNSPro. Chaque machine cliente exécute l'application Tickets : les utilisateurs ouvrent des tickets depuis la zone de notification et les techniciens répondent depuis le panneau web — avec un terminal en direct sur la machine, des suggestions d'IA supervisée, l'exécution de commandes à distance et des annonces vers des sites ou départements entiers.

<p align="center"><img src="./screenshots/website.png" width="640" alt="capture"></p>

## Fonctionnalités

- **Tickets par machine** — les utilisateurs ouvrent et suivent leurs tickets depuis l'app de la zone de notification ; chaque ticket est lié à sa machine et à son site.
- **Terminal en direct** — exécutez cmd/PowerShell sur la machine cliente depuis le panneau, avec une sortie visible par l'utilisateur.
- **IA supervisée** — réponses suggérées et aide aux commandes pour les techniciens (Pro+).
- **Commandes à distance** — exécutez des commandes validées en tant que SYSTEM sans interrompre l'utilisateur (Pro+).
- **Annonces** — communications vers des sites ou départements entiers avec accusé de lecture.
- **Vue de la machine** — matériel, services et état de la machine du ticket sur le même écran (Básico+).
- **Base de connaissances** — réponses réutilisables et documentation interne (Pro+).
- **Marque blanche** — votre marque dans l'application (Business).
- **Rôles** — permissions des techniciens : voir, traiter, exécuter, admin.
- **Six langues** — portail et application en ES / EN / FR / IT / DE / PT.

## Mode d'emploi

1. Inscrivez-vous ou souscrivez une offre sur [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) (l'offre Gratuite couvre jusqu'à 5 machines).
2. **Machines avec l'Agent** : activez Tickets sur la machine — l'application s'installe toute seule en quelques minutes, rien à télécharger.
3. **Machines isolées** : installez `DynamicDNSPro-Tickets-Setup.exe` et associez-la avec le jeton de liaison affiché dans *Paramètres* du panneau.
4. Invitez vos techniciens, attribuez les rôles et répondez aux tickets — avec terminal, IA et commandes à distance sur les offres payantes.

## Éditions & tarifs

| Offre | Prix | Machines | Inclut |
|---|---|---|---|
| **Gratuit** | 0 € | 5 | Tickets, terminal en direct, annonces |
| **Básico** | 6 €/mois · 60 €/an | Illimitées | Tout Gratuit + vue serveur de la machine |
| **Pro** | 12 €/mois · 120 €/an | Illimitées | + IA supervisée, commandes à distance, base de connaissances |
| **Business** | 24 €/mois · 240 €/an | Illimitées | + marque blanche (votre marque dans l'app) |

## Prérequis

Windows 10/11 x64 · Accès Internet vers `tickets.dynamicdnspro.com` · Pour l'association, le jeton de liaison dans *Paramètres* (installations isolées) ou l'Agent DynamicDNSPro (déploiement automatique).

## Contenu de ce dépôt

- `DynamicDNSPro-Tickets-Setup-<version>.exe` — installateur Windows versionné
- `DynamicDNSPro-Tickets-Setup.exe` — copie à nom stable pointant vers la dernière release
- `version.json` — flux de mise à jour automatique (`tickets_url` / `tickets_size`) servi par le portail

[Dernière release](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest)

## FAQ

**Ai-je besoin de cet installateur sur les machines avec l'Agent DynamicDNSPro ?**  
Non — activez Tickets sur la machine dans le panneau et l'agent déploie l'application automatiquement via le canal fleet signé.

**Comment les machines isolées sont-elles liées à mon compte ?**  
Après l'installation, l'application demande le jeton de liaison affiché dans *Paramètres → Jetons* de votre portail tickets.

**Que comprend l'offre Gratuite ?**  
Tickets, terminal en direct et annonces jusqu'à 5 machines — sans carte bancaire.

## Support

- Site & portail client : [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com)
- E-mail : support@it-systems.es

---
<p align="center"><sub>DynamicDNSPro Tickets · © MavkSoft / IT-Systems</sub></p>
