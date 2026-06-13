---
title: Unit - 332 AEW
tags: [unit]
type: unit
aliases: [332nd Air Expeditionary Wing]
---

## Unit data

designation:: 332nd Air Expeditionary Wing
parent_command:: AFCENT / USCENTCOM
home_station:: [[Location - Muwaffaq Salti Air Base]]
aircraft:: [[Platform - F-15E Strike Eagle]]; F-16; MQ-9; etc.
typical_mission:: OIR fighter, ISR, and strike

## Incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  platform AS "Platform"
FROM "03 - Incidents"
WHERE contains(unit, this.file.link)
SORT date_event DESC
```
