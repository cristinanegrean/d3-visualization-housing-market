# d3-visualization-housing-market

Get [Elsevier may 2017 graphs on Dutch Housing Market](http://www.elsevierweekblad.nl/onderzoek/achtergrond/2017/05/vind-uw-wijk-wat-is-uw-huis-werkelijk-waard-498706/) in data-driven-documents with https://d3js.org/

### Steps for creating NL Cartogram with d3 & TopoJSON

1) Geospatial Data Abstraction Library, commonly referred as [GDAL], a multitool binary to use for manipulating the Natural Earth shape files.

```
brew install gdal
```

2) Install reference implementation for [TopoJSON](https://www.npmjs.com/package/topojson), which requires Node.js. TopoJSON is an extension of GeoJSON that encodes topology. Combined with fixed-precision encoding for coordinates, TopoJSON is usually much smaller than GeoJSON.

```
npm install -g topojson@1
```

and verify installation:

```
which ogr2ogr
which topojson
``
