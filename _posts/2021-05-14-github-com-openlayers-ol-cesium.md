---
title: ol-cesium
categories: ['javascript', 'cesium', 'openlayers']
---
## [ol-cesium](https://github.com/openlayers/ol-cesium)

### OpenLayers - Cesium integration

```bash
npm i --save olcs
```

Then import the parts you need. Example:
```js
import OLCesium from 'olcs/OLCesium.js';
const ol3d = new OLCesium({map: ol2dMap}); // ol2dMap is the ol.Map instance
ol3d.setEnabled(true);
```

For Cesium integration see [ol-cesium-webpack-example](https://github.com/gberaudo/ol-cesium-webpack-example)
based on the official `Cesium With Webpack` example.
