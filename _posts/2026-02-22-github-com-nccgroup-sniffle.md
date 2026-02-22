---
title: Sniffle
categories: ['python', 'ble', 'bluetooth']
---
## [Sniffle](https://github.com/nccgroup/Sniffle)

### A sniffer for Bluetooth 5 and 4.x LE


**Sniffle is a sniffer for Bluetooth 5 and 4.x (LE) using TI CC1352/CC26x2 hardware.**

Sniffle has a number of useful features, including:

* Support for BT5/4.2 extended length advertisement and data packets
* Support for BT5 Channel Selection Algorithms #1 and #2
* Support for all BT5 PHY modes (regular 1M, 2M, and coded modes)
* Support for sniffing only advertisements and ignoring connections
* Support for channel map, connection parameter, and PHY change operations
* Support for advertisement filtering by MAC address and RSSI
* Support for BT5 extended advertising (non-periodic)
* Support for capturing advertisements from a target MAC on all three primary
  advertising channels using a single sniffer. **This makes connection detection
  nearly 3x more reliable than most other sniffers that only sniff one advertising
  channel.**
* Easy to extend host-side software written in Python
* PCAP export compatible with the Ubertooth
* Wireshark compatible plugin
