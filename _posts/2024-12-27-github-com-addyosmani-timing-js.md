---
title: timing.js
categories: ['javascript']
---
## [timing.js](https://github.com/addyosmani/timing.js)

### Navigation Timing API measurement helpers


* Normalizes `firstPaint` across Chrome, Opera and IE11 to `timing.getTimes().firstPaint`. Firefox may be able to do similar with `MozAfterPaint`
* Adds `firstPaintTime` (`firstPaint` - load/nav start)
* Adds:`domReadyTime`, `initDomTreeTime`, `loadEventTime`, `loadTime`, `redirectTime`, `requestTime`, `unloadEventTime` `connectTime`
