---
title: throttle
categories: ['javascript', 'throttle', 'bandwith']
---
## [throttle](https://github.com/sitespeedio/throttle)

### Throttle your network connection [Linux/Mac OS X]

Inspired by [tylertreat/Comcast](https://github.com/tylertreat/Comcast), the [connectivity setting in the WPTAgent](https://github.com/WPO-Foundation/wptagent/blob/master/internal/traffic_shaping.py) and [sltc](https://github.com/sitespeedio/sltc).

Throttle uses *pfctl* on Mac and *tc* on Linux to simulate different network speeds. On Linux you also need *ip* and *route* for Throttle to work.

You can set the download/upload speed and RTT. Upload/download is in kbit/s and RTT in ms.

This is an early release, so please help us find potential bugs.
