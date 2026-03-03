---
title: Overworld map
draft: false
prioritise: true
---

> [!warning] Non-canon
> 
> The player characters are currently unaware of the full map, and only know the places they explored. This map exists for the convience of the players.

```base
filters: file.hasProperty("marker")
views:
  - type: leaflet-map
    name: Map
    mapName: overworld-map
    image: rainforest-map.png
    minZoom: -1.5
    maxZoom: 2
    defaultZoom: -1.5
    zoomDelta: 0.5
    scale: "0.2"
    height: 400
    unit: km
```