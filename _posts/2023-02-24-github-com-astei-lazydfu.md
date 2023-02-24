---
title: lazydfu
categories: ['java', 'minecraft-mod', 'minecraft-performance']
---
## [lazydfu](https://github.com/astei/lazydfu)

### Fabric mod that makes Minecraft DataFixerUpper initialization lazy


LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" - that is, it
will not immediately create the rules required to migrate data from older versions of Minecraft to
newer versions until it actually needs to do so. It does not modify DFU and should be safe, but do
exercise more than the usual caution.

The premise of LazyDFU is simple: most of the time, you will not need to convert data for every version
of the game. As a result, DFU rule compilation occurs later, when the game is already up and running.
This means it is possible you may see lag spikes if LazyDFU forces the game to compile migration rules,
but once complete there is no performance penalty.
