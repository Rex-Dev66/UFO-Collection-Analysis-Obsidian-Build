---
title: Sensor - EO IR
tags: [sensor, sensor/eoir]
type: sensor
aliases: [EO/IR, Electro-Optical Infrared, FLIR]
---

## Specifications

type:: Electro-optical / infrared sensor (general category)
band:: Visible + LWIR (8-12 micron) + MWIR (3-5 micron) depending on system
host_platform:: Most modern military aircraft and many platforms

## Detection characteristics

EO/IR is the dominant sensor type for modern UAP detection because it provides a visual image (rather than a return strength like radar) and is not jammed by radio-frequency electronic attack. EO/IR also produces artifacts that have been mistaken for genuine objects: lens reflections, image processing artifacts, hot pixels, and "ghost" returns from internal optics.

The "white hot" thermal signature commonly reported for UAPs in this collection indicates the object is warmer than its background. For an object against open sky or water, almost any solid object will appear warm; this is not in itself evidence of an exotic energy source.

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
