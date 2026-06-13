---
title: Unit - HSM-73
tags: [unit]
type: unit
aliases: [Helicopter Maritime Strike Squadron 73, Battlecats]
---

## Unit data

designation:: Helicopter Maritime Strike Squadron 73 ("Battlecats")
parent_command:: Commander, Helicopter Maritime Strike Wing Pacific
home_station:: NAS North Island, California
aircraft:: [[Platform - MH-60R Seahawk]]
typical_mission:: ASW, SUW, SSC from CG/DDG/FFG and CVN

## Incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(unit, this.file.link)
SORT date_event DESC
```
