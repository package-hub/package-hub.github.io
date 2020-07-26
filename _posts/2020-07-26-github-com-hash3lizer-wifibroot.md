---
title: WiFiBroot
categories: ['python', 'wpa2', 'pmkid']
---
## [WiFiBroot](https://github.com/hash3liZer/WiFiBroot)

### A Wireless (WPA/WPA2) Pentest/Cracking tool. Captures & Crack 4-way handshake and PMKID key. Also, supports a deauthentication/jammer mode for stress testing

WiFiBroot is built to provide clients all-in-one facility for cracking WiFi (WPA/WPA2) networks. It heavily depends on **scapy**, a well-featured packet manipulation library in Python. Almost every process within is dependent somehow on scapy layers and other functions except for operating the wireless interface on a different channel. That will be done via native linux command **iwconfig** for which you maybe need *sudo* privileges. It currently provides **four** independent working modes to deal with the target networks. Two of them are online cracking methods while the other runs in offline mode. The offline mode is provided to crack saved hashes from the first two modes. One is for deauthentication attack on wireless network and can also be used as a jamming handler. It can be run on a variety of linux platforms and atleast requires WN727N from tp-link to properly operate. 
