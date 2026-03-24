---
title: Rifts
draft: false
---

Rifts that appeared during the Shattering (March 1, 2023). Rifts lead to specific places on the [[Overworld]]. To return after entering a Rift, a power crystal is needed.

Rifts have a "countdown" until new monsters are spawned in the overworld, which is delayed by killing monsters after entering the portal. A [[Crown System#Riftwarden]] can see this counter.

# Rift Locations
This section contains the locations of various rifts. There is also a list of [[Unspecified Rifts|rifts whose exact location is currently uncertain]].
## The Netherlands
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

## The United States of America
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

## The Middle East
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

## China
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

## South America
```base
filters: file.hasProperty("marker")
views:
  - type: leaflet-map
    name: Map
    mapName: south-america-rifts
    image: map-of-south-america.jpg
    minZoom: 0
    maxZoom: 2
    defaultZoom: -1
    zoomDelta: 0.5
    scale: "0.2"
    height: 400
    unit: km
```