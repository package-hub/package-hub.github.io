---
title: Karta
categories: ['python', 'research', 'ida-plugin']
---
## [Karta](https://github.com/CheckPointSW/Karta)

### Karta - source code assisted fast binary matching plugin for IDA

"Karta" (Russian for "Map") is an IDA Python plugin that identifies and matches open-sourced libraries in a given binary. The plugin uses a unique technique that enables it to support huge binaries (>200,000 functions), with almost no impact on the overall performance.

The matching algorithm is location-driven. This means that it's main focus is to locate
the different compiled files, and match each of the file's functions based on their original order within the file. This way, the matching depends on K (number of functions in the open source) instead of N (size of the binary), gaining a significant performance boost as usually N >> K.

We believe that there are 3 main use cases for this IDA plugin:
1. Identifying a list of used open sources (and their versions) when searching for a useful 1-Day
2. Matching the symbols of supported open sources to help reverse engineer a malware
3. Matching the symbols of supported open sources to help reverse engineer a binary / firmware when searching for 0-Days in proprietary code
