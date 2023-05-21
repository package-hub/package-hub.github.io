---
title: cadmus
categories: ['python']
---
## [cadmus](https://github.com/josh-richardson/cadmus)

### A GUI frontend for @werman's Pulse Audio real-time noise suppression plugin

Whilst software exists on Windows & MacOS (Krisp, RTX Voice, etc) to remove background noise from recorded audio in real-time, no user-friendly solution seemed to exist on Linux. Cadmus was written to address this shortcoming, allowing users to remove background noise from audio in Discord/Zoom/Skype/Slack/etc calls without having to use the commandline. It is primarily a GUI frontend for @werman's [PulseAudio Noise Suppression Plugin](https://github.com/werman/noise-suppression-for-voice).

When you run Cadmus, you'll see a new notification icon showing a microphone in your chosen shell. On click, you'll be able to select the microphone whose noise you wish to suppress. Cadmus will then create a new PulseAudio microphone named `Cadmus Denoised Output`, which will reflect the denoised output of the chosen microphone. You should then be able to select this as an input in any application of your choice. Note that if you're currently recording audio, you'll have to stop recording and start again in order for changes to occur - streams which are currently being recorded will not be hot-swapped to the new input.      
