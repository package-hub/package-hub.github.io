---
title: picosnitch
categories: ['python', 'networking', 'security']
---
## [picosnitch](https://github.com/elesiuta/picosnitch)

### Monitor Network Traffic Per Executable, Beautifully Visualized

- 🔔 Receive notifications whenever a new program connects to the network, or when it's modified
- 📈 Monitors your bandwidth, breaking down traffic by executable, hash, parent, domain, port, or user over time
- 🌍 Web and terminal interfaces with GeoIP lookups for each connection ([IP Geolocation by DB-IP](https://db-ip.com))
- 🛡️ Can optionally check hashes or executables using [VirusTotal](https://www.virustotal.com)
- 🚀 Executable hashes are cached based on device + inode for improved performance
- 🐳 Detects applications running inside containers, multiple versions of the same app are differentiated based on their hash
- 🕵️ Uses [BPF](https://ebpf.io/) for [accurate, low overhead bandwidth monitoring](https://www.gcardone.net/2020-07-31-per-process-bandwidth-monitoring-on-Linux-with-bpftrace/) and [fanotify](https://man7.org/linux/man-pages/man7/fanotify.7.html) to watch executables for modification
- 👨‍👦 Since applications can call others to send/receive data for them, the parent executable and hash is also logged for each connection
- 🧰 Pragmatic and minimalist design focusing on [accurate detection with clear and reliable error reporting when it isn't possible](#limitations)
