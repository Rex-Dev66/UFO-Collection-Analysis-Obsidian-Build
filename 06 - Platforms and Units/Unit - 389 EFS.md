---
title: Unit - 389 EFS
tags: [unit]
type: unit
aliases: [389th Expeditionary Fighter Squadron, 389 EFS]
---

## Unit data

designation:: 389th Expeditionary Fighter Squadron
parent_command:: [[Unit - 332 AEW]] / AFCENT / USCENTCOM
home_station:: Mountain Home AFB ID (home); [[Location - Muwaffaq Salti Air Base]] (forward)
aircraft:: [[Platform - F-15E Strike Eagle]]
typical_mission:: DCA, SCAR, strike in support of [[Operation Inherent Resolve]]

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
