# UFO Visualizations — Altair + Vega-Lite

[Click here to view the interactive visualizations](https://sabrinachunyin.github.io/ufo-viz/)

Below are static previews of the plots:

## Plot 1 — Annual Trend of UFO Reports in the U.S.
This area + line chart shows how UFO sighting reports have changed from 1940 to 2015.  
Encodings: *x = year (temporal)*, *y = number of reports (quantitative)*.  
Color was intentionally excluded to focus attention on the temporal trend.  
Data transformation: grouped by year to aggregate the total number of reports.

---

## 👁Plot 2 — Interactive UFO Sightings Map
This interactive scatter map visualizes the geographic distribution of UFO sightings across the U.S.  
Encodings: *x = longitude*, *y = latitude*, *color = shape*, *size = duration (seconds)*.  
Interactivity: A year slider allows filtering by time, and clicking on the legend highlights specific UFO shapes.  
This interaction helps users explore how UFO sighting shapes and regions vary by year.
