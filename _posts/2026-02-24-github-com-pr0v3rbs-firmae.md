---
title: FirmAE
categories: ['python', 'emulation', 'firmware']
---
## [FirmAE](https://github.com/pr0v3rbs/FirmAE)

### Towards Large-Scale Emulation of IoT Firmware for Dynamic Analysis


FirmAE is a fully-automated framework that performs emulation and vulnerability analysis. FirmAE significantly increases the emulation success rate (From [Firmadyne](https://github.com/firmadyne/firmadyne)'s 16.28% to 79.36%) with five arbitration techniques. We tested FirmAE on 1,124 wireless-router and IP-camera firmware images from top eight vendors.

We also developed a dynamic analysis tool for 0-day discovery, which infers web service information based on the filesystem and kernel logs of target firmware.
By running our tool on the succesfully emulation firmware images, we discovered 12 new 0-days which affect 23 devices.
