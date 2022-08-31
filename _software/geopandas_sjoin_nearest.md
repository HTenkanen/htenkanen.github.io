---
title: "geopandas `sjoin_nearest()` method"
collection: software
permalink: software/geopandas_sjoin_nearest
---

GeoPandas is an open source Python project and one of the core libraries in Python for doing GIS and working with geospatial data. 
The goal of GeoPandas is to make working with geospatial data in Python easier. I have contributed to `geopandas` by prototyping and suggesting 
a new feature `.sjoin_nearest()`, read more below.

![Geopandas logo](geopandas_logo.png)

### Documentation

You can read more about `geopandas` from the [documentation](https://geopandas.org/) of the library. 
The documentation for the `sjoin_nearest()` method can be read [from here](https://geopandas.org/en/stable/docs/reference/api/geopandas.sjoin_nearest.html).

### My role

I contributed to `geopandas` by suggesting and creating a prototype of the method `sjoin_nearest()` that allows to make a 
spatial join of two GeoDataFrames based on the distance between their geometries. The feature was kindly later implemented by [@adriangb](https://github.com/adriangb)
and geopandas core developer team. 

Links:
- [Issue #1096](https://github.com/geopandas/geopandas/issues/1096) suggesting and prototyping this feature.
- [PR #1865](https://github.com/geopandas/geopandas/pull/1865) adding this functionality to geopandas.
