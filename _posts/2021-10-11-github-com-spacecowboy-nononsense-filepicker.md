---
title: NoNonsense-FilePicker
categories: ['java']
---
## [NoNonsense-FilePicker](https://github.com/spacecowboy/NoNonsense-FilePicker)

### A file/directory-picker for android. Implemented as a library project.


In Kitkat or above, use Android's built-in file-picker instead. Google has restricted the ability of external libraries like this from creating directories on external SD-cards in Kitkat and above which will manifest itself as a crash.

If you need to support pre-Kitkat devices see [#158](https://github.com/spacecowboy/NoNonsense-FilePicker/issues/158#issuecomment-353896387) for the recommendation approach.

This does not impact the library's utility for non-SD-card locations, nor does it impact you if you don't want to allow a user to create directories.
