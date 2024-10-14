---
title: JSONCrush
categories: ['javascript', 'json', 'url-shortener']
---
## [JSONCrush](https://github.com/KilledByAPixel/JSONCrush)

### Compress JSON into URL friendly strings


This simple system allows for excellent compression of uri encoded JSON strings using the JSCrush algorithm.

* The JSCrush algorithm eliminates repeated substrings similar to the zip algorithm.
* Strings are processed to swap out common json characters with ones that won't be escaped in the URL.
* This can be used to compress any type of string but is optimized for uri encoded JSON.
* The algorithm speed is reasonable for most cases but can be slow for long strings (>10K characters).
* The character \u0001 (start of heading) is used as a delimiter and will be removed if it appears.
* No additional libraries or dependencies are required and minified code is under 2k!
