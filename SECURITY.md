# Security Policy — DynamicDNSPro Tickets

DynamicDNSPro Tickets is distributed through this repository as signed binary releases.

## Verifying a download

- Windows binaries are built on our self-hosted runner and released only
  through this repository — compare the download URL against the official
  release page before running.
- Auto-updates are fetched over verified TLS and signature-checked
  (EdDSA / SHA-256 with automatic rollback where supported).
- The app pairs to your account with a per-installation link token —
  keep it private; you can rotate it from the panel at any time.

## Reporting a vulnerability

Please report security issues privately to
**support@it-systems.es** — do not open a public issue for
vulnerabilities. We aim to acknowledge reports within 48 hours.

## Privacy

See https://tickets.dynamicdnspro.com for the product privacy policy. The
application is designed to run locally; where the product uses an account
or cloud service, only the data required for the feature is transmitted.
