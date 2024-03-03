---
title: Twitch-HLS-AdBlock
categories: ['javascript', 'twitch', 'ads']
---
## [Twitch-HLS-AdBlock](https://github.com/instance01/Twitch-HLS-AdBlock)

### Block advertisements that are inserted in Twitch streams directly.


Twitch is playing a 15-30 second advertisement whenever one starts watching a new channel. For people who jump around a bit this is pretty annoying.

Twitch staff has been fairly quick to remove client side fixes that disable advertisements. Since they're able to inject advertisementst into the HLS stream directly ([SSAI](https://aws.amazon.com/blogs/media/why-is-server-side-ad-insertion-important/), Twitch's [SureStream](http://twitchadvertising.tv/ad-products/surestream/) if you want to research further), I believe such fixes will not always be available.

This extension monkey patches the web worker (among others) Twitch uses and edits the m3u8 playlist that gets requested every few seconds to simply remove segments that are marked as advertisments with SCTE-35 flags.

Right now Twitch also makes the actual stream available in those playlist files after a few seconds, which means that after just around 5 seconds the real stream begins, instead of 30 seconds of advertisements.
