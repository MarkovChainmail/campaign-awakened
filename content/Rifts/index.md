---
title: Known Rifts
draft: false
---

# The Netherlands
```base
filters: file.hasProperty("marker")
views:
  - type: leaflet-map
    name: Map
    mapName: netherlands-rifts
    image: Map_provinces_Netherlands-en.svg.png
    minZoom: -1.5
    maxZoom: 2
    defaultZoom: -0.5
    zoomDelta: 0.5
    scale: "0.2"
    height: 400
    unit: km
```

# The United States of America
```base
filters: file.hasProperty("marker")
views:
  - type: leaflet-map
    name: Map
    mapName: usa-rifts
    image: map_of_the_united_states.jpg
    minZoom: -3.5
    maxZoom: 2
    defaultZoom: -3.5
    zoomDelta: 0.5
    scale: "0.2"
    height: 400
    unit: km
```