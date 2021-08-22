---
title: external-nfc-api
categories: ['java', 'android', 'nfc']
---
## [external-nfc-api](https://github.com/skjolber/external-nfc-api)

### Interaction with external NFC readers in Android

Library for interaction with ACS NFC readers over USB; external NFC support Android devices. 

Features:
 - External NFC reader management and interaction
 - Parallell use of external and/or internal NFC (i.e. in the same activity, both enabled at the same time)
 - Support for both tags and Android devices (Host Card Emulation), simultaneously
 - Use of forked `android.nfc` classes ([Ndef], [MifareUltralight], [IsoDep], etc) for Android 10+ support.

As this project very much simplifies implementation for use-cases requiring external NFC readers, it saves a lot of development time (2-8 weeks depending on use-case and previous knowledge).

Bugs, feature suggestions and help requests can be filed with the [issue-tracker]. __DO NOT send me emails unless you're prepared to pay for my time.__
