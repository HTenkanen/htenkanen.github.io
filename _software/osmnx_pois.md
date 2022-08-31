---
title: "OSMnx - Retrieve Point of Interest (POI) data -functionalities"
collection: software
permalink: software/osmnx_pois
date: 2018-01-01
---

`osmnx` is an open source Python project and one of the core libraries in Python for retrieving and working with OpenStreetMap data.  
`osmnx` lets you download geospatial data from OpenStreetMap and model, project, visualize, and analyze real-world street networks 
and any other geospatial geometries. I contributed to `osmnx` by adding features to extract Point of Interest data from the OpenStreetMap data.
Since these contributions (in 2018), the library has evolved and there is a new API design to fetch geometries of any type with specific tags.


### Documentation

You can read more about `osmnx` from the [documentation](https://osmnx.readthedocs.io/en/stable/) of the library. 
The latest documentation to download OSM geometric entities (such as POIs) with `osmnx.geometries` -module 
can be read [from here](https://osmnx.readthedocs.io/en/stable/osmnx.html#module-osmnx.geometries).

### My role

I contributed to `osmnx` by adding `pois_from_address()`, `pois_from_place()`, `pois_from_polygon()` functionalities 
(+ some internal mechanisms to make this happen) that allowed to retrieve Point of Interest data from OSM into a `GeoDataFrame`. 

Links:
- [Pull Request #146](https://github.com/gboeing/osmnx/pull/146) adding this feature.
- [Related issue #116](https://github.com/gboeing/osmnx/issues/116)
