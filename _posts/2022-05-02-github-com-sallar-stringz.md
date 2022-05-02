---
title: stringz
categories: ['typescript', 'unicode', 'substr']
---
## [stringz](https://github.com/sallar/stringz)

### :100: Super fast unicode-aware string manipulation Javascript library


A really small, performant, unicode-aware library for working
with Strings in Node.js.

Javascript has a serious problem with unicode. Even ES6 can’t solve the problem
entirely since some characters like the new colored emojis are three bytes
instead of two bytes. Sometimes even more! `"👍🏽".length` returns `4` which is
totally wrong (hint: it should be 1!). ES6's `Array.from` tried to solve this,
but that even fails: `Array.from("👍🏽")` returns `["👍", "🏽"]` which is
incorrect. This library tries to tackle all these problems with a mega RegExp.
[Read More Here](https://mathiasbynens.be/notes/javascript-unicode).
