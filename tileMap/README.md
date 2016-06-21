Using [d3.geo.tile](https://github.com/d3/d3-plugins/tree/master/geo/tile) to display raster image tiles underneath some [TopoJSON](https://github.com/mbostock/topojson) vectors, and [d3.behavior.zoom](https://github.com/mbostock/d3/wiki/Zoom-Behavior) for pan & zoom. This version adjusts the transform and stroke-width to update the displayed vector data efficiently. You can instead [reproject interactively](/mbostock/5342063), but changing the transform is typically much faster. Also see the [static version](/mbostock/94b9fd26e12c586f342d).

Tiles copyright [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).