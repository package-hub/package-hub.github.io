---
title: lunasec
categories: ['typescript', 'tokenization', 'web-security']
---
## [lunasec](https://github.com/lunasec-io/lunasec)

### LunaSec - Open Source Security Software built by Security Engineers. Scan your dependencies for Log4Shell, or add Data Tokenization to prevent data leaks. Try our live Tokenizer demo: https://app.lunasec.dev


We're a team of Security Engineers on a mission to make awesome Open Source Application Security tooling. It all lives
in this repo. Here's a breakdown of everything we've built.

- **[Log4Shell CLI](./tools/log4shell)**: A small command line utility to scan for Log4Shell. Also supports patching JAR files against 
 Log4Shell, scanning running processes on your system, and more. Follow our 
 [Mitigation Guide](https://www.lunasec.io/docs/blog/log4j-zero-day-mitigation-guide/) for more context. 
    - **Status**: Production ready.
- **[LunaTrace](./lunatrace)**: A vulnerability scanner and web dashboard that helps track vulnerabilities in real-time. Combines static analysis,
dynamic analysis, and live-patching into an enterpise-grade vulnerability solution.
    - **Status**: Under active development.
- **[LunaDefend](https://www.lunasec.io/docs/pages/overview/features/)**: An end-to-end suite of security software built 
 around Tokenization designed to _proactively_ protect your sensitive data from being hacked, as well as providing an 
 easier path towards compliance (SOC2, GDPR, PCI-DSS, etc).
    - **Status**: Production ready.
- **[Our Security Blog](https://www.lunasec.io/docs/blog/)**: Our ramblings to the internet. This is where we broke the news about the log4j vulnerability and gave it the name [Log4Shell](https://www.lunasec.io/docs/blog/tags/log-4-shell).  The blog lives in this repo under `/docs/blog` if you feel 
 like contributing!
