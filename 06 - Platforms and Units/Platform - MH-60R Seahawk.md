---
title: Platform - MH-60R Seahawk
tags: [platform, platform/mh-60r]
type: platform
aliases: [MH-60R, Romeo, Seahawk]
---

## Specifications

type:: Anti-submarine and surface warfare helicopter
role:: ASW, SUW, SAR, Surface Search Coordination (SSC)
service:: U.S. Navy (operated from CG, DDG, FFG, and carriers)
primary_sensor:: APS-153 radar, ALFS dipping sonar, AAS-44 FLIR
typical_mission:: SSC, ASW, SAR

## Incidents reported from this platform

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  shape AS "Shape",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(platform, this.file.link)
SORT date_event DESC
```

## Notes

MH-60R routinely operates at low altitudes over water in maritime surveillance roles, which gives it a perspective on low-altitude air contacts that fast movers miss. Range Fouler reports from MH-60R squadrons can capture small slow contacts that would not be of interest to fighter or AWACS sensor pipelines.
