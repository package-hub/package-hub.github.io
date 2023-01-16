---
title: local-npm
categories: ['javascript', 'node', 'npm']
---
## [local-npm](https://github.com/local-npm/local-npm)

### Local and offline-first npm mirror


`local-npm` acts as a proxy between you and the main npm registry. You run `npm install` commands like normal, but under the hood, all requests are sent through the local server.

When you first `npm install` a module, it'll be fetched from the main npm registry. After that, the module and all its dependencies (at that version) are stored in a local database, so you can expect subsequent installs to be much faster.

The server will also listen for changes from the remote registry, so you can expect updates to a module's metadata to be replicated within seconds of being published. (I.e. you won't get stuck with old versions.)

If you're organizing a conference/meetup/whatever, you can also share this local server with multiple people.  So if your teammates are constantly installing the same modules over and over again, this can save a lot of time in the long run.

`local-npm` is also a good way to make `npm install` work offline. Assuming new versions of a package haven't been published since you last installed, subsequent `npm install`s will all serve from the cache, without ever hitting a remote server.

Addy Osmani has [a nice post](https://addyosmani.com/blog/using-npm-offline/) comparing `local-npm` to other options.
