# yuktix-open-weather
Visualizations for open weather data in Bangalore. Part of the [Yuktix Open Weather Project](www.yuktix.com/open-weather-project/)

[![image](https://cloud.githubusercontent.com/assets/68416/16123545/02fa6d70-3409-11e6-96bf-f240029353d2.png)](http://bl.ocks.org/curran/de831e1e04057147f612456460047df4)
A first prototype piece, visualizing a snapshot of temperature around Bangalore.

Goals:

 * Use D3 to make a replacement for this [Open Weather Project Map](http://www.yuktix.com/m/aws/). We can draw from [Raster & Vector III](http://bl.ocks.org/mbostock/5914438) for the background map of Bangalore, and render stations as circles with voronoi clipping, like in this example [Circle Dragging IV](http://bl.ocks.org/mbostock/ec10387f24c1fad2acac3bc11eb218a5). We can color the circles based on data using [D3 color scales](https://github.com/d3/d3-scale#interpolateViridis).
 * Create a map visualization showing temperature at each weather station. This will be a kind of choropleth map, with the areas defined as circles around each station with voronoi clipping applied. The marks for each station may look like this:

[![image](https://cloud.githubusercontent.com/assets/68416/16123617/52cd4458-3409-11e6-99d4-e56bba597afb.png)](http://bl.ocks.org/mbostock/ec10387f24c1fad2acac3bc11eb218a5)

 * Create a [calendar view](https://bl.ocks.org/mbostock/4063318) of rainfall history.
