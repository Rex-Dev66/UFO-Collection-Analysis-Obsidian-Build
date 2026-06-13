---
title: Unit - Unit Designation
tags: [unit]
type: unit
aliases: []
---

## Unit data

designation:: 
parent_command:: 
home_station:: 
aircraft:: [[Platform - ]]
typical_mission:: 

## Incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  platform AS "Platform",
  status AS "Status"
FROM "02 - Incidents"
WHERE contains(unit, this.file.link)
SORT date_event DESC
```

## Notes

Historical context, deployment cycles, any notable patterns in this unit's UAP encounters.
