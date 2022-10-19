---
title: mp4box.js
categories: ['javascript']
---
## [mp4box.js](https://github.com/gpac/mp4box.js)

### JavaScript version of GPAC's MP4Box tool

Similar to `MP4Box -info file.mp4`, MP4Box.js can provide general information about the file (duration, number and types of tracks ...). For that, create an MP4Box ISOFile object, set the `onReady` callback and provide data in the form of ArrayBuffer objects. MP4Box.js supports progressive parsing. You can provide small buffers at a time, the callback will be called when the 'moov' box is parsed.

```javascript
var MP4Box = require('mp4box'); // Or whatever import method you prefer.
var mp4boxfile = MP4Box.createFile();
mp4boxfile.onError = function(e) {};
mp4boxfile.onReady = function(info) {};
mp4boxfile.appendBuffer(data);
mp4boxfile.appendBuffer(data);
mp4boxfile.appendBuffer(data);
...
mp4boxfile.flush();
```
