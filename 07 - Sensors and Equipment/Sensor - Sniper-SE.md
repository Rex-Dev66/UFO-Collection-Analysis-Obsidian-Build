---
title: Sensor - Sniper-SE
tags: [sensor, sensor/eoir]
type: sensor
aliases: [Sniper Advanced Targeting Pod, Sniper XR SE]
---

## Specifications

type:: Electro-optical / infrared targeting pod
host_platform:: [[Platform - F-15E Strike Eagle]] and various USAF fighters
manufacturer:: Lockheed Martin

## Detection characteristics

Provides air-to-ground laser designation, EO and IR imagery with high zoom, and air-to-air tracking. Capable of producing "white hot" / "black hot" polarity imagery similar to ATFLIR. The SE variant adds extended-range improvements over the original Sniper pod.

UAP imagery captured by Sniper pods generally appears as small bright or dark blobs depending on polarity, with little surface detail unless the object is large or close. Most published UAP sensor stills from CENTCOM are consistent with Sniper or ATFLIR output.

## Incidents using this sensor

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(sensor, this.file.link)
SORT date_event DESC
```
