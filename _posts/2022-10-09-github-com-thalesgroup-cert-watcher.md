---
title: Watcher
categories: ['python', 'cybersecurity', 'threat-hunting']
---
## [Watcher](https://github.com/thalesgroup-cert/Watcher)

### Watcher - Open Source Cybersecurity Threat Hunting Platform. Developed with Django & React JS.


- Detecting emerging cybersecurity trends like new vulnerabilities, malwares... Via social networks & other RSS feeds (www.cert.ssi.gouv.fr, www.cert.europa.eu, www.us-cert.gov, www.cyber.gov.au...).
- Monitor for information leaks, for example in Pastebin & other IT content exchange websites (stackoverflow, github, gitlab, bitbucket, apkmirror, npm...).
- Monitor malicious domain names for changes (IPs, mail/MX records, web pages using [TLSH](https://github.com/trendmicro/tlsh)).
- Detecting suspicious domain names targeting your organisation, using:
     - [dnstwist](https://github.com/elceef/dnstwist) algorithm.
     - Certificate transparency stream: [certstream](https://github.com/CaliDog/certstream-python)

Useful as a bundle regrouping threat hunting/intelligence automated features.
