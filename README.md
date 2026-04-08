# 🔭 IOC Pivot Hub

**Paste any IOC — pivot instantly to 30+ threat intelligence platforms.**

→ **[Live tool](https://dgiry.github.io/ioc-pivot)**

---

## What it does

Paste a single IOC and get one-click links to every major threat intel platform — no API keys, no account, no data sent anywhere. 100% client-side.

| IOC Type | Platforms |
|----------|-----------|
| **IP Address** | VirusTotal, Shodan, AbuseIPDB, GreyNoise, Censys, IPinfo, Talos, OTX, ThreatFox, BGP.he.net |
| **Domain** | VirusTotal, URLscan.io, Shodan, Talos, OTX, ThreatFox, Censys, Whois, MXToolbox, BGP.he.net |
| **URL** | VirusTotal, URLscan.io, URLhaus, Talos, OTX, Google Safe Browsing |
| **Hash** (MD5/SHA1/SHA256) | VirusTotal, MalwareBazaar, Hybrid Analysis, Any.run, ThreatFox, OTX, MalShare, Talos |
| **Email** | VirusTotal, EmailRep, HaveIBeenPwned, Hunter.io, MXToolbox, ThreatFox |
| **CVE** | NVD NIST, CVE.org, MITRE, Exploit-DB, Tenable, AttackerKB, GitHub Advisory, CIRCL, VulnCheck |

## Features

- **Auto-detection** — paste any IOC, type is detected instantly
- **Auto-refang** — defanged input (`185[.]220[.]101[.]45`, `hxxps://`, `evil[.]ru`) is automatically normalized
- **Open all** — one click opens every platform in new tabs
- **Filter by category** — Reputation / OSINT / Threat Intel / Sandbox / Exploit…
- **Copy link** — share a pre-filled URL (`?ioc=...`)
- **URL param mode** — `https://dgiry.github.io/ioc-pivot?ioc=185.220.101.45`
- **Zero backend** — static HTML, no data leaves your browser

## Usage

```
https://dgiry.github.io/ioc-pivot?ioc=185.220.101.45
https://dgiry.github.io/ioc-pivot?ioc=CVE-2024-21887
https://dgiry.github.io/ioc-pivot?ioc=44d88612fea8a8f36de82e1278abb02f
```

## Companion tool

**[🔬 Defang IOC](https://dgiry.github.io/defang-ioc)** — extract and defang/refang IOCs from threat reports. Use the **🔭 Pivot** button to send any IOC directly here.

## Deploy your own

Static HTML — works on GitHub Pages, Netlify, Vercel, or any web server.

```bash
git clone https://github.com/dgiry/ioc-pivot
# open index.html in your browser
```

## Contributing

PRs welcome — especially new platforms, bug fixes, or additional IOC types.

## License

MIT
