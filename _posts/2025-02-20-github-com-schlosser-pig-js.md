---
title: pig.js
categories: ['javascript']
---
## [pig.js](https://github.com/schlosser/pig.js)

### Arrange images in a responsive, progressive-loading grid managed in JavaScript using CSS transforms.


Arrange images in a responsive, progressive-loading grid managed in JavaScript using CSS transforms, with one lightweight library. Here's what you get:

1. **Performance**: The `pig.js` grid specializes in displaying a large number of photos. While a more traditional approaches would paginate images, or use AJAX to load and insert buckets of additional images onto the page, `pig.js` intelligently loads and unloads images as you scroll down the page, to ensure ensure speedy rendering of images, smooth scrolling, and minimal network activitiy.
2. **Responsiveness**: Images are loaded in JavaScript, at different resolutions depending on screen size. Also, because images are positioned using CSS transforms, images smartly re-tile when you shrink or expand the browser window.
3. **User Experience**: Images are previewed with a small placeholder image that is scaled and blured.  When the image loads, it gives the effect that the image was brought into focus (it's super cool!).

A lot of this is stolen straight from Google Photos (by way of observation and some creative use of the Chrome Inspector) and Medium (by way of some [dope blog posts](https://jmperezperez.com/medium-image-progressive-loading-placeholder/)).

If you want to see `pig.js` in action, check out the site that motivated it in the first place: a catalog of everything I ate in 2015: [feeding.schlosser.io][feeding-dan].  That site is also [on GitHub][feeding-dan-gh].
