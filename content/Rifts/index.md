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

# The Middle East
```base
filters: file.hasProperty("marker")
views:
  - type: leaflet-map
    name: Map
    mapName: middleeast-rifts
    image: Map_of_Middle_East.png
    minZoom: -0.5
    maxZoom: 2
    defaultZoom: -0.5
    zoomDelta: 0.5
    scale: "0.2"
    height: 400
    unit: km
```

# China
```base
filters: file.hasProperty("marker")
views:
  - type: leaflet-map
    name: Map
    mapName: china-rifts
    image: provinces-of-china-map.png
    minZoom: -1
    maxZoom: 2
    defaultZoom: -1
    zoomDelta: 0.5
    scale: "0.2"
    height: 400
    unit: km
```