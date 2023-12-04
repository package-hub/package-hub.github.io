---
title: Gaussholder
categories: ['php']
---
## [Gaussholder](https://github.com/humanmade/Gaussholder)

### Fast and lightweight image previews, using Gaussian blur


Gaussholder is inspired by [Facebook Engineering's fantastic post][fbeng] on generating tiny preview images. Gaussholder takes the concepts from this post and applies them to the wild world of WordPress.

In a nutshell, Gaussholder takes a Gaussian blur and applies it to an image to generate a preview image. Gaussian blurs work as a low-pass filter, allowing us to throw away a lot of the data. We then further reduce the amount of data per image by removing the JPEG header and rebuilding it on the client side (this eliminates ~800 bytes from each image).

We further reduce the amount of data for some requests by lazyloading images.

[fbeng]: https://code.facebook.com/posts/991252547593574
