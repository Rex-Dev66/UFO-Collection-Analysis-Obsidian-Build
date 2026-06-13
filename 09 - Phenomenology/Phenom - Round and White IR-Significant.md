---
title: Phenom - Round and White IR-Significant
tags: [phenom, phenom/round, phenom/white-hot]
type: phenom
---

> [!SUMMARY]
> The dominant phenomenological description in this collection: round or spherical objects appearing white or "white hot" in IR sensors, typically without radar return, observed for seconds to minutes.

## Definition

A small (apparently meter-scale to small-aircraft scale) round or spherical object that reads as warmer than its background in infrared sensors. Often appears against open sky, water, or distant terrain.

## Incidents matching

```dataview
LIST
FROM "03 - Incidents"
WHERE contains(file.tags, "#phenom/round") OR contains(file.tags, "#phenom/white-hot")
SORT date_event DESC
```

## Conventional candidates

- Small UAS (drones, especially fixed-wing or quadcopter with warm motor/battery)
- Weather balloons and surveillance balloons
- Mylar party balloons
- Birds against thermal-bright backgrounds
- Aerostat platforms
- Lens flares or hot pixels in sensor (rare in modern systems but documented)

## Analytical note

The "round white hot" descriptor is so consistent across the collection that it should be treated as the default category, not the exceptional one. Future incident notes should explicitly state when an observation does ==not== match this baseline.
