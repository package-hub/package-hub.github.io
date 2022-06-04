---
title: element-desktop
categories: ['typescript', 'element', 'element-web']
---
## [element-desktop](https://github.com/vector-im/element-desktop)

### A glossy Matrix collaboration client for desktop.


TODO: List native pre-requisites

Optionally, [build the native modules](https://github.com/vector-im/element-desktop/blob/develop/docs/native-node-modules.md), 
which include support for searching in encrypted rooms and secure storage. Skipping this step is fine, you just won't have those features.  

Then, run
```
yarn run build
```
This will do a couple of things:
 * Run the `setversion` script to set the local package version to match whatever
   version of Element you installed above.
 * Run electron-builder to build a package. The package built will match the operating system
   you're running the build process on.
