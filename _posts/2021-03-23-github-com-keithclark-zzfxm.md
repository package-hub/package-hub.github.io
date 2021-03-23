---
title: ZzFXM
categories: ['javascript', 'music-player', 'game-development']
---
## [ZzFXM](https://github.com/keithclark/ZzFXM)

### A super small music generator for use in size-limited JavaScript productions


This is a music generator for use in tiny JavaScript productions (i.e. js13k games). ZzFXM uses a modified version of the super-tiny [ZzFX library](https://github.com/KilledByAPixel/ZzFX) by [Frank Force](https://twitter.com/KilledByAPixel) to generate instruments. The modified version of ZzFX is able create an array of audio data without immediately playing it.

The song format is loosely based on the MOD format, using patterns to handle repeating blocks of song data. Unlike MOD, patterns can be variable in length allowing repeatitive sequences of pattern data to be broken down into smaller chunks. Each pattern can also contain a variable number of channels, reducing the need to store empty data.

