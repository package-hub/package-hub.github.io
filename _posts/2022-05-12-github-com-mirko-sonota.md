---
title: SonOTA
categories: ['python']
---
## [SonOTA](https://github.com/mirko/SonOTA)

### Flashing Itead Sonoff devices with custom firmware via original OTA mechanism


A script to update a Sonoff device from the stock firmware to [Sonoff-Tasmota](https://github.com/arendst/Sonoff-Tasmota/) purely over WiFi.

This is **beta** software, and it may not work 100% of the time, and require to manually flash your device using serial. Although it can not be guaranteed, it's unlikely the device will be damaged such that it can't be flashed with Sonoff-Tasmota via serial (the difficulty of this depends on the device and the headers in provides). Typically if it does not work, a power cycle restores the functionality to the default firmware.
