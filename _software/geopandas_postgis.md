---
title: "geopandas `to_postgis()` method"
collection: software
permalink: software/geopandas_postgis
---


GeoPandas is an open source Python project and one of the core libraries in Python for doing GIS and working with geospatial data. 
The goal of GeoPandas is to make working with geospatial data in Python easier. I have contributed to `geopandas` by adding a new feature `.to_postgis()`, read more below.

![Geopandas logo](geopandas_logo.png)

### Documentation

You can read more about `geopandas` from the [documentation](https://geopandas.org/) of the library. 
The documentation for the `to_postgis()` method can be read [from here](https://geopandas.org/en/stable/docs/reference/api/geopandas.GeoDataFrame.to_postgis.html).

### My role

I contributed to `geopandas` by adding a method `to_postgis()` that allows to write the `GeoDataFrame` to PostGIS database. 
Previously, it was only possible to read data from PostGIS, but not the other way around.

Links:
- [Pull Request #1248](https://github.com/geopandas/geopandas/pull/1248) adding this feature.
- [Related issue #595](https://github.com/geopandas/geopandas/issues/595)
