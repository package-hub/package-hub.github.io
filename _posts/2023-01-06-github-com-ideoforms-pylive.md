---
title: pylive
categories: ['python']
---
## [pylive](https://github.com/ideoforms/pylive)

### Query and control Ableton Live from Python


**NOTE: Work is currently underway on updating pylive to interface with [AbletonOSC](https://github.com/ideoforms/AbletonOSC) for Live 11 support, hopefully for completion in December 2022.**

PyLive is a framework for querying and controlling Ableton Live from a standalone Python script, mediated via Open Sound Control. It is effectively an interface to the Live Control Surfaces paradigm, which means it can do anything that a hardware control surface can do, including:

 - query and modify global parameters such as tempo, volume, pan, quantize, arrangement time
 - query and modify properties of tracks, clips, scenes and devices
 - trigger and stop clips and scenes

It can perform most of the operations described in the [LiveOSC OSC API](https://github.com/hanshuebner/LiveOSC/blob/master/OSCAPI.txt).

If you are looking simply to send MIDI messages to Live, this module is not what you want. Instead, try setting up a [virtual MIDI bus](https://help.ableton.com/hc/en-us/articles/209774225-How-to-setup-a-virtual-MIDI-bus) and using [isobar](https://ideoforms.github.io/isobar/) to generate MIDI sequences.
