---
title: lvmsync
categories: ['ruby']
---
## [lvmsync](https://github.com/mpalmer/lvmsync)

### Synchronise LVM LVs across a network by sending only snapshotted changes


Have you ever wanted to do a partial sync on a block device, possibly over a
network, but were stymied by the fact that rsync just didn't work?

Well, fret no longer.  As long as you use LVM for your block devices, you
too can have efficient delta-transfer of changed blocks.

