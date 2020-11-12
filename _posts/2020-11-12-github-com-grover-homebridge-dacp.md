---
title: homebridge-dacp
categories: ['javascript', 'homebridge', 'homebridge-plugin']
---
## [homebridge-dacp](https://github.com/grover/homebridge-dacp)

### Remotely control Apple TV and iTunes via HomeKit.


This platform plugin enables Homebridge to control devices or programs, which implement [DACP](https://en.wikipedia.org/wiki/Digital_Audio_Control_Protocol). Examples of programs or
devices that can be controlled by this plugin are Apple TV and iTunes.

Any system capable of running [Homebridge](https://github.com/nfarina/homebridge) can be
used to run `homebridge-dacp`. The only need is network access to the device or program in
question. There is no need to run this on the same machine as iTunes to expose it via HomeKit.

homebridge-dacp provides volume control and play/pause controls via HomeKit. These can be
used in conjunction with the [homebridge-callmonitor plugin](https://github.com/grover/homebridge-callmonitor)
to pause media playback or to reduce the playback volume while on a phone call.

The Speaker service, which provides volume control and mute, can be disabled if it is not
required - for example if the Apple TV is connected to an A/V receiver that is integrated
with HomeKit via a different plugin.
