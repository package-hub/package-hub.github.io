---
title: EMVemulator
categories: ['java', 'android', 'emv-smartcard-protocol']
---
## [EMVemulator](https://github.com/MatusKysel/EMVemulator)

### This Android app collects Mag-Stripe data and CVC3 codes from PayPass cards and emulates that information.  

**IMPORTANT - THIS REPO IS NO LONGER MAINTAINED**

This Android app collects Mag-Stripe data and CVC3 codes from MasterCard PayPass cards and emulates that information.
It is based on combined pre-play and downgrade attack described in [Cloning Credit Cards: A combined pre-play and downgrade attack on EMV Contactless](https://github.com/MatusKysel/EMVemulator/raw/master/Cloning%20Credit%20Cards%20A%20combined%20pre-play-Roland.pdf) by Michael Roland, Josef Langer.

**WARNING!** This application might destroy your credit card (MasterCard only) after ~ 66 successful attacks.*

*For each attack application increments card's ATC by 1000. ATC (Application Transaction Counter) is 2B value that means that maximum value of ATC is 65535, so after approximately 66 attacks this counter overflows.
