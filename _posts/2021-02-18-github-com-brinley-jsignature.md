---
title: jSignature
categories: ['javascript']
---
## [jSignature](https://github.com/brinley/jSignature)

### jQuery plugin for adding web signature functionality


jSignature is a jQuery plugin which simplifies creation of a signature capture field in the browser window, allowing a user to draw a signature using mouse, pen, or finger.

jSignature captures signature as vector outlines of the strokes. Although jSignature can export great bitmap (PNG) too, extraction of highly scalable stroke movement coordinates (aka vector image) of the signature allows much greater flexibility of signature rendering.

A extra effort (through smoothing and pressure simulation) is made to make the strokes look pretty on the screen while these are drawn by the signor.

All major desktop, tablet and phone browsers are supported. HTML5 Canvas element is used by default. We fall back on Flash-based Canvas element emulator (FlashCanvas) when actual Canvas is not supported by the browser (Internet Explorer v.8 and lower).

Real-time jSignature renders only the device-appropriate "prettiest" approximation of what we capture. Capture of data is always same - we capture as many movement coordinates as possible. Rendering of strokes differs per browser's capabilities, efficiency of the device, screen size.

This degrading and enhancing of screen representation of the captured signature is done on purpose to insure that rendering does not impead on the responsiveness of capture.
For example, on slow rendering devices (Android Browser, FlashCanvas-based Canvas emulation) smoothing is kicked up a notch to compensate for large gaps in captured stroke coordinates - a result of inefficiency of capture device. In all cases, customer shold be pleased by responsiveness and beauty of the drawing.

jSignature makes it easy to pluck itself into an existing styled site. jSignature automatically detects the colors used on the wrapping element (text color = pen color, background = background) and auto-picks a pleasing middle-shade for 'decor' (signature line). jSignature adapts well to fixed and variable width web page designs, and various size screens (phones, tablets, computer screens) and automatically rescales the drawing area and signature when parent element changes size.

See [demos here](http://brinley.github.io/jSignature/ "Signature Capture Demos").
