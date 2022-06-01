---
title: smbmap
categories: ['python']
---
## [smbmap](https://github.com/ShawnDEvans/smbmap)

### SMBMap is a handy SMB enumeration tool


SMBMap allows users to enumerate samba share drives across an entire domain. List share drives, drive permissions, share contents, upload/download functionality, file name auto-download pattern matching, and even execute remote commands. This tool was designed with pen testing in mind, and is intended to simplify searching for potentially sensitive data across large networks.

Some of the features have not been thoroughly tested, so changes will be forth coming as bugs are found. I only really find and fix the bugs while I'm on engagements, so progress is a bit slow. Any feedback or bug reports would be appreciated. It's definitely rough around the edges, but I'm just trying to pack in features at the moment. Version 2.0 should clean up the code a lot….whenever that actually happens ;). Thanks for checking it out!!

There's a known oddity in the SMBServer component used for the file content search feature. For some reason it throws an exception in the threading library. It still works, but the error is annoying none the less.
