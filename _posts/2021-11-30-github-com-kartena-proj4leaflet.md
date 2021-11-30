---
title: Proj4Leaflet
categories: ['javascript']
---
## [Proj4Leaflet](https://github.com/kartena/Proj4Leaflet)

### Smooth Proj4js integration with Leaflet.


This [Leaflet](http://leafletjs.com) plugin adds support for using projections supported by
[Proj4js](https://github.com/proj4js/proj4js).

_Proj4Leaflet uses Leaflet 1.0.3, for compatibility with Leaflet 0.7.x use the [0.7.2](https://github.com/kartena/Proj4Leaflet/releases/tag/0.7.2) release._

Leaflet comes with built in support for tiles in [Spherical Mercator](http://wiki.openstreetmap.org/wiki/EPSG:3857) and [a few other projections](http://leafletjs.com/reference-1.0.0.html#crs-l-crs-epsg3395). 
If you need support for tile layers in other projections, the Proj4Leaflet plugin lets you use tiles in any projection 
supported by Proj4js, which means support for just about any projection commonly used.

Proj4Leaflet also adds support for GeoJSON in any projection, while Leaflet by itself assumes GeoJSON to always 
use WGS84 as its projection.

Image overlays with bounds set from projected coordinates rather than `LatLng`s are also supported by Proj4Leaflet plugin.

For more details, see this blog post on [tiling and projections](http://www.liedman.net/2012/07/02/local-projections-in-a-world-of-spherical-mercator/).
