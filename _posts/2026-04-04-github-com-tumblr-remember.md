---
title: Remember
categories: ['java']
---
## [Remember](https://github.com/tumblr/Remember)

### A preferences-backed key-value store


An in-memory data store backed by shared preferences, for Android.

This is a key-value store with some nice properties:

1. Speed. Everything is loaded into memory so reads can happen on the UI thread. Writes and deletes happen asynchronously (with callbacks). Every public method is safe to call from the UI thread.

2. Durability. Writes get persisted to disk, so that this store maintains state even if the app closes or is killed.

3. Consistency. Doing a write followed by a read should return the value you just put.

4. Thread-safety. Reads and writes can happen from anywhere without the need for external synchronization.

Note that since writes are asynchronous, an in-flight write may be lost if the app is killed before the data has been written to disk. If you require true 'commit' semantics then Remember is not for you.
