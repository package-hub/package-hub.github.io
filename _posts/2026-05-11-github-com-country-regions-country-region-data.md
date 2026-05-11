---
title: country-region-data
categories: ['javascript', 'country-list', 'region-list']
---
## [country-region-data](https://github.com/country-regions/country-region-data)

### A source list of countries, regions and shortcodes in JSON and JS format.


This repo provides country and region data in three different formats: ESM, UMD (Unified Module Definition) and
plain JSON. The data contains country names, country short codes, country regions, and country region short
codes. All country names and short codes are guaranteed to be unique. Similarly, all regions and region short
codes _within a single country_ are guaranteed to be unique.

Countries can subdivide themselves in all sorts of different ways, often overlapping. They may have states, provinces,
regions, districts, municipalities, and more. The goal of this repo was to house whatever subdivisions makes sense from
the viewpoint of _addressing_, and for that we use [ISO-3166-2](https://en.wikipedia.org/wiki/ISO_3166-2).

The raw data here is used for the [country-region-selector](https://github.com/country-regions/country-region-selector),
[react-country-region-selector](https://github.com/country-regions/react-country-region-selector) scripts but can be used
independently for whatever you want.
