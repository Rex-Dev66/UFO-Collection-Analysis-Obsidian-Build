---
title: Platform - F-15E Strike Eagle
tags: [platform, platform/f-15e]
type: platform
aliases: [F-15E, Strike Eagle, Mudhen]
---

## Specifications

type:: Tandem-seat multirole strike fighter
role:: Air-to-air, air-to-ground, DCA, SCAR
service:: U.S. Air Force
primary_sensor:: [[Sensor - APG-82 Radar]]
secondary_sensors:: [[Sensor - Sniper-SE]] targeting pod; ALR-56C RWR
typical_mission:: DCA over Syria/Iraq, deep strike, CAS

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

F-15E radar (APG-82 AESA) is high resolution but EO/IR primary visual identification is via the Sniper-SE pod. The aircraft is two-seat (pilot and weapons systems officer), which provides two trained observers per aircraft per sortie. The 2-ship standard formation provides 4 sets of trained eyes plus 2 sensor packages on any given DCA mission.
