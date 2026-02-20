---
title: Watcher
categories: ['javascript', 'cybersecurity', 'threat-hunting']
---
## [Watcher](https://github.com/thalesgroup-cert/Watcher)

### Watcher - Open Source AI-powered Cyber Threat Intelligence & Hunting Platform. Developed with Django & React JS.


Watcher empowers your security operations with comprehensive threat detection and monitoring:

- **AI-Driven Threat Intelligence** — Transform raw threat data into actionable intelligence with automated weekly digests of top-5 trending cybersecurity topics, real-time breaking news alerts when threats emerge, on-demand summaries for any security keyword including related CVE and threat actor details.

- **Emerging Threat Detection** — Monitor cybersecurity trends via RSS feeds from CERT-FR (www.cert.ssi.gouv.fr), CERT-EU (www.cert.europa.eu), US-CERT (www.us-cert.gov), Australian Cyber Security Centre (www.cyber.gov.au), and more. Track new vulnerabilities, malware campaigns, and threat advisories as they appear.

- **Legitimate Domain Management** — Centralized approved domains with expiry, repurchase status, registrar info, and contacts. Easily convert monitored malicious domains into legitimate ones.

- **Information Leak Monitoring** — Detect sensitive data exposure across the webs including Pastebin, StackOverflow, GitHub, GitLab, Bitbucket, APKMirror, npm registries, and other platforms. Catch leaked credentials, API keys, and confidential information early.

- **Malicious Domain Surveillance** — Monitor malicious domains for changes in IP addresses, mail/MX records, and web content. Use [TLSH](https://github.com/trendmicro/tlsh) fuzzy hashing to detect modifications. Automatic RDAP/WHOIS checks with registrar and expiry alerts.

- **Suspicious Domain Detection** — Identify potentially malicious domains targeting your organisation via:
  - **Domain Generation Algorithm Detection** using [dnstwist](https://github.com/elceef/dnstwist) to find typosquatting, homograph attacks, and similar domain variants
  - **Certificate Transparency Monitoring** via [certstream](https://github.com/CaliDog/certstream-python) to catch newly registered suspicious domains in real-time
