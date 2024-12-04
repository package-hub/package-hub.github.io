---
title: passkit-generator
categories: ['typescript', 'apple', 'wallet']
---
## [passkit-generator](https://github.com/alexandercerutti/passkit-generator)

### The easiest way to generate custom Apple Wallet passes in Node.js


This library was created with a specific architecture in mind: **application** and **model** (as preprocessed entity), to split as much as possible static objects (such as logo, background, icon, etc.) from dynamic ones (translations, barcodes, serialNumber, ...), while keeping an eye on the different possible execution contexts.

Pass creation and population might not fully happen in runtime. This library allows to create a pass from scratch, specify a folder model (template) or specify a set of buffers. In the last two cases, both should contain all the objects needed (static medias) and structure to make a pass work.

Whenever adding files, through scratch, template or buffer, these will be read and pushed as they are in the resulting .zip file, while dynamic data will be patched (`pass.json` with props) or generated in runtime (`manifest.json`, `signature` and translation files).
