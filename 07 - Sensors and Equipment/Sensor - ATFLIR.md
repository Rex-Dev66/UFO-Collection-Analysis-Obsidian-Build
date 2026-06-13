---
title: Sensor - ATFLIR
tags: [sensor, sensor/atflir]
type: sensor
aliases: [Advanced Targeting Forward-Looking Infrared, AN/ASQ-228]
---

## Specifications

type:: Electro-optical / infrared targeting pod (Navy)
host_platform:: F/A-18E/F Super Hornet, F/A-18C/D legacy Hornet
manufacturer:: Raytheon

## Detection characteristics

Air-to-air and air-to-ground EO/IR with high zoom. The pod has Block I and Block II variants with different sensor resolutions. ATFLIR Block II is the source of the well-known 2004 USS Nimitz "Tic Tac" video and many subsequent Navy UAP recordings.

ATFLIR autotrack is a common field on the Navy Range Fouler Debrief Form. When the autotrack box is NOT checked, the pilot was manually maintaining track, which is a limitation for sustained observation.

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

## Notes

The visual style of ATFLIR imagery (white-hot or black-hot polarity, crosshair reticle, scale hash marks, target designation indicator) is the dominant aesthetic of the [[FBI Photo Series Index|FBI Photo series]] in this collection, suggesting most or all of those frames are Navy ATFLIR origin.
