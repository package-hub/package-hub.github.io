---
title: mobile-drag-drop
categories: ['typescript']
---
## [mobile-drag-drop](https://github.com/timruffles/mobile-drag-drop)

### A drop-in shim to allow you to use existing html5 drag'n'drop code with mobile browsers


The HTML 5 drag'n'drop API allows you to implement drag'n'drop on [most desktop browsers and some mobile browsers](http://caniuse.com/#search=drag). 

~~Unfortunately, you'll notice most mobile browsers don't support it, so no iPad (or Nexus) action for you!~~

`Chrome>=96 on Android>=7` and `Safari on iOS/iPadOS>=15` are reported to support drag and drop natively!
This means native support for drag and drop is growing but some browsers still need polyfilling.
It is advised to keep an eye on [caniuse](http://caniuse.com/#search=drag) and test for your userbase.
In the case of iOS native support and the polyfill seem to be able to coexist without issues.

See https://github.com/timruffles/mobile-drag-drop/issues/167 for state of drag and drop in `iOS/iPad>=15`.

`Chrome>=96 on Android>=7` behaviour is under investigation.

Luckily, browsers give us enough tools to make it happen ourselves if needed. If you drop
this package in your page your existing HTML 5 drag'n'drop code should _just work_ ([*almost](#polyfill-requires-dragenter-listener)).

