---
title: "An app for kriging"
layout: app
published: true
category: apps
tags: [spatial, kriging, mapping]
short: kriging
link: "http://206.167.180.241:3838/kriging/"
summary: "This app makes kriging easy."
---

This app does the kriging for you!
It is as simple as one, two, three:

1. upload your data ([CSV file format](https://en.wikipedia.org/wiki/Comma-separated_values), [WGS 84](https://epsg.io/4326) coordinate system]),
2. interactively edit the map to subset the observations and inspect the distribution of values ([Box-Cox transformation](https://en.wikipedia.org/wiki/Power_transform#Box.E2.80.93Cox_transformation) is done when necessary),
3. pick a [variogram](https://en.wikipedia.org/wiki/Variogram) model, view and download the predictions in [Geo TIFF](https://en.wikipedia.org/wiki/GeoTIFF) raster format.

**Note:** large (*n* > 1000) data sets are randomly sampled (*n* = 1000) to speed up calculations.
