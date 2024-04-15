---
title: buffer-backed-object
categories: ['javascript']
---
## [buffer-backed-object](https://github.com/GoogleChromeLabs/buffer-backed-object)

### Buffer-backed objects in JavaScript.


**`BufferBackedObject` creates objects that are backed by an `ArrayBuffer`**. It takes a schema definition and de/serializes data on-demand using [`DataView`][dataview] under the hood. The goal is to make [`ArrayBuffer`][arraybuffer]s more convenient to use.

```
npm i -S buffer-backed-object
```
