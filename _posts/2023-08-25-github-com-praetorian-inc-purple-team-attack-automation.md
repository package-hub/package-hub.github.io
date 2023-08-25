---
title: purple-team-attack-automation
categories: ['ruby']
---
## [purple-team-attack-automation](https://github.com/praetorian-inc/purple-team-attack-automation)

### Praetorian's public release of our Metasploit automation of MITRE ATT&CK™ TTPs


At Praetorian, we were seeking a way to automatically emulate adversary tactics in order to evaluate detection and response capabilities. Our solution implements MITRE ATT&CK&trade; TTPs as Metasploit Framework `post` modules. As of this release, we've automated a little over 100 TTPs as modules.

Metasploit's advantage is its robust library, capability to interact with operating system APIs, and its flexible license. In addition, we're able to emulate the features of other tools such as in-memory .NET execution via leveraging Metasploit's `execute_powershell` functionality. This allows Blue Teams to ensure that their tools are alerting on the actual TTP behavior and not execution artifacts (such as encoded PowerShell).

Our solution is built on top of the latest version of Metasploit as of 09Apr2019 (pulled from: https://github.com/rapid7/metasploit-framework). We’ve made minor modifications to Metasploit’s code base to enable some of the automation. Everything should work as intended if you’re already familiar with Metasploit. The magic happens after you establish a Meterpreter session and run a TTP as a post-exploitation module.

We're open sourcing our work because we believe in solving the cybersecurity problem. By giving Blue Teams more tools to emulate adversary behavior, we hope to improve their capabilities and reduce the still very high average dwell time.
