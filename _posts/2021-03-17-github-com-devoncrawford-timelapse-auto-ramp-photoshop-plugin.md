---
title: Timelapse-Auto-Ramp-Photoshop-Plugin
categories: ['java']
---
## [Timelapse-Auto-Ramp-Photoshop-Plugin](https://github.com/DevonCrawford/Timelapse-Auto-Ramp-Photoshop-Plugin)

### Analyze RAW images from a timelapse, and auto - ramp the exposure for manual changes of camera settings. The best way to achieve amazing results in difficult lighting.


My favourite project so far. This program is made for timelapse photographers (like me) to use with photoshop!

My algorithm simply looks for changes in shutter speed, aperture, and iso, then mathematically calculates the exposure offset required to match the difference between a change in two pictures, evenly applies the exposure change across leading images, and writes new exposure to the RAW (.xmp) files. This allows photoshop or after effects to access my calculations with no issue, and use the ramped values when rendering. This makes best use in difficult lighting conditions such as a timelapse of a sunrise, where your best option is to change the exposure manually, as the sun rises. If you did not use this technique you will notice flickering on auto mode, or stick with one setting on manual, making some parts underexposed and others overexposed.
