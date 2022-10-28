---
title: scroll-js
categories: ['typescript', 'scrolling', 'scroller']
---
## [scroll-js](https://github.com/markcellus/scroll-js)

### Light cross-browser scroller that uses native javascript


A light-weight library that will allow you to scroll any html element using native javascript.
In addition to providing extra scrolling features, this library also aims to be a polyfill for the [scrollTo](https://developer.mozilla.org/en-US/docs/Web/API/Window/scroll)
and [scrollIntoView](https://drafts.csswg.org/cssom-view/#dom-element-scrollintoview) APIs and allows you to scroll
using animations that are based loosely on the
[`scrollOptions` of the DOM specification](https://drafts.csswg.org/cssom-view/#dictdef-scrolloptions).
Manipulates native scroll properties so that native events fire appropriately and uses browser's animation frames for
fast and smooth rendering.
