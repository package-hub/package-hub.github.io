---
title: react-qr-reader
categories: ['javascript', 'reactjs', 'react']
---
## [react-qr-reader](https://github.com/JodusNodus/react-qr-reader)

### React component for reading QR codes from webcam.


A [React](https://facebook.github.io/react/) component for reading QR codes from the webcam. It uses the WebRTC standards for reading webcam data and [jsQR](https://github.com/cozmo/jsQR) is used for detecting QR codes in that data. To optimise the speed and experience, a web-worker is used to offload the heavy QR code algorithm on a separate process. The web worker is inlined and loaded on creation of the component.
