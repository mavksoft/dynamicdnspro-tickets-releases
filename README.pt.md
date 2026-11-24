<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="DynamicDNSPro Tickets" width="96">
</p>

<h1 align="center">DynamicDNSPro Tickets</h1>

<p align="center">Suporte técnico com um agente na máquina.<br>Tickets de suporte, terminal ao vivo, IA supervisionada e avisos — a partir do painel web ou da própria app.</p>

<p align="center">
  <a href="https://tickets.dynamicdnspro.com"><img src="https://img.shields.io/badge/site-tickets.dynamicdnspro.com-0A84FF" alt="site"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-tickets-releases?label=última" alt="última release"></a>
  <img src="https://img.shields.io/badge/plataforma-Windows-black" alt="plataformas">
  <img src="https://img.shields.io/badge/licença-comercial-orange" alt="licença comercial">
</p>

<p align="center"><a href="https://mavksoft.github.io/dynamicdnspro-tickets-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/dynamicdnspro-tickets-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <strong>🇵🇹 Português</strong></p>

> **Este repositório publica apenas releases binárias oficiais** — o código-fonte é privado. Downloads assinados e feeds de auto-atualização.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-tickets-releases/main/icons/windows.svg' width='15' style='vertical-align:-2px' alt='windows'> **Tickets (Windows)** | [DynamicDNSPro-Tickets-Setup.exe](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest/download/DynamicDNSPro-Tickets-Setup.exe) — sempre a última build estável |
| <img src='https://dynamicdnspro.com/assets/img/logo.png' width='15' style='vertical-align:-2px'> **Site** | [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) — portal do cliente, planos e gestão |

Em máquinas com o **Agente DynamicDNSPro** não é preciso instalador: ativa o Tickets na máquina (ou em toda a conta) e a app instala-se sozinha.

## O que é

O DynamicDNSPro Tickets é o módulo de suporte técnico do ecossistema DynamicDNSPro. Cada máquina cliente corre a app Tickets: os utilizadores abrem tickets a partir da bandeja do sistema e os técnicos respondem no painel web — com terminal ao vivo na máquina, sugestões de IA supervisionada, execução remota de comandos e avisos para sedes ou departamentos inteiros.

<p align="center"><img src="./screenshots/website.png" width="640" alt="captura"></p>

## Funcionalidades

- **Tickets por máquina** — os utilizadores abrem e acompanham tickets a partir da app da bandeja; cada ticket fica ligado à sua máquina e sede.
- **Terminal ao vivo** — executa cmd/PowerShell na máquina cliente a partir do painel, com saída visível para o utilizador.
- **IA supervisionada** — respostas sugeridas e ajuda com comandos para técnicos (Pro+).
- **Comandos remotos** — executa comandos validados como SYSTEM sem interromper o utilizador (Pro+).
- **Avisos** — comunicados para sedes ou departamentos inteiros com confirmação de leitura.
- **Vista da máquina** — hardware, serviços e estado da máquina do ticket no mesmo ecrã (Básico+).
- **Base de conhecimento** — respostas reutilizáveis e documentação interna (Pro+).
- **Marca branca** — a tua marca dentro da app (Business).
- **Funções** — permissões de técnico: ver, atender, executar, admin.
- **Seis idiomas** — portal e app em ES / EN / FR / IT / DE / PT.

## Como usar

1. Regista-te ou contrata um plano em [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com) (o plano Grátis cobre até 5 máquinas).
2. **Máquinas com o Agente**: ativa o Tickets na máquina — a app instala-se sozinha em minutos, sem descarregar nada.
3. **Máquinas avulsas**: instala o `DynamicDNSPro-Tickets-Setup.exe` e associa-a com o token de ligação mostrado em *Definições* do painel.
4. Convida os teus técnicos, atribui funções e começa a responder tickets — com terminal, IA e comandos remotos nos planos pagos.

## Edições e preços

| Plano | Preço | Máquinas | Inclui |
|---|---|---|---|
| **Grátis** | 0 € | 5 | Tickets, terminal ao vivo, avisos |
| **Básico** | 6 €/mês · 60 €/ano | Ilimitadas | Tudo do Grátis + vista de servidor da máquina |
| **Pro** | 12 €/mês · 120 €/ano | Ilimitadas | + IA supervisionada, comandos remotos, base de conhecimento |
| **Business** | 24 €/mês · 240 €/ano | Ilimitadas | + marca branca (a tua marca na app) |

## Requisitos

Windows 10/11 x64 · Acesso à Internet para `tickets.dynamicdnspro.com` · Para associar, o token de ligação em *Definições* (instalações avulsas) ou o Agente DynamicDNSPro (implantação automática).

## O que há neste repositório

- `DynamicDNSPro-Tickets-Setup-<versão>.exe` — instalador Windows versionado
- `DynamicDNSPro-Tickets-Setup.exe` — cópia de nome estável que aponta para a última release
- `version.json` — feed de auto-atualização (`tickets_url` / `tickets_size`) servido pelo portal

[Última release](https://github.com/mavksoft/dynamicdnspro-tickets-releases/releases/latest)

## FAQ

**Preciso deste instalador em máquinas com o Agente DynamicDNSPro?**  
Não — ativa o Tickets na máquina no painel e o agente instala a app automaticamente pelo canal fleet assinado.

**Como se associam as máquinas avulsas à minha conta?**  
Depois de instalar, a app pede o token de ligação mostrado em *Definições → Tokens* do teu portal de tickets.

**O que inclui o plano Grátis?**  
Tickets, terminal ao vivo e avisos até 5 máquinas — sem cartão.

## Suporte

- Site e portal do cliente: [tickets.dynamicdnspro.com](https://tickets.dynamicdnspro.com)
- Email: support@it-systems.es

---
<p align="center"><sub>DynamicDNSPro Tickets · © MavkSoft / IT-Systems</sub></p>
