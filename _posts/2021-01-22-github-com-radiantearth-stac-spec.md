---
title: stac-spec
categories: ['python', 'satellites', 'satellite-imagery']
---
## [stac-spec](https://github.com/radiantearth/stac-spec)

### SpatioTemporal Asset Catalog specification - making geospatial assets openly searchable and crawlable


The SpatioTemporal Asset Catalog (STAC) specification aims to standardize the way geospatial assets are exposed online and queried. 
A 'spatiotemporal asset' is any file that represents information about the earth captured in a certain space and 
time. The initial focus is primarily remotely-sensed imagery (from satellites, but also planes, drones, balloons, etc), but 
the core is designed to be extensible to SAR, full motion video, point clouds, hyperspectral, LiDAR and derived data like
NDVI, Digital Elevation Models, mosaics, etc. 

The goal is for all major providers of imagery and other earth observation data to expose their data as SpatioTemporal Asset 
Catalogs, so that new code doesn't need to be written whenever a new JSON-based REST API comes out that makes its data 
available in a slightly different way. This will enable standard library components in many languages. STAC can also be
implemented in a completely 'static' manner, enabling data publishers to expose their data by simply publishing linked JSON
files online.
