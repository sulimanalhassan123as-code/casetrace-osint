# CaseTrace — OSINT Investigation Console

**Professional open-source intelligence (OSINT) console** for public-source investigation, evidence-led case management, and reproducible assessment records.

## Features

- **Multi-target support** — Phone numbers, email addresses, usernames, domains, and other identifiers
- **8+ pivot sources per type** — Google, Bing, DuckDuckGo, Truecaller, WHOIS, VirusTotal, Wayback Machine, HIBP, and more
- **5-stage assessment pipeline** — Target intake → Metadata → OSINT pivots → Evidence log → Report assembly
- **Live terminal output** — Real-time investigation log with timestamps
- **Case history** — Session-persisted case list for quick recall
- **Export** — JSON and HTML report formats with evidence-led formatting
- **Ethical by design** — Explicit limitations, no private data access, no fabricated results

## Ethical Stance

CaseTrace does **not**:
- Access private messages, device data, or carrier records
- Infer subscriber identity from a number alone
- Fabricate or manufacture forensic results
- Present speculative data as confirmed intelligence

All findings are limited to what can be independently verified through open sources.

## Deploy

```bash
git clone https://github.com/sulimanalhassan123as-code/casetrace-osint.git
cd casetrace-osint
npx vercel
```

Or simply open `index.html` in a browser.

## License

Open source — use responsibly.
