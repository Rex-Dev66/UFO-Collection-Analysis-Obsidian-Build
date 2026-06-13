---
title: Unit - 196 ATKS
tags: [unit, aor/centcom]
type: unit
aliases: [196th Attack Squadron, 196 ATKS, 163d Attack Wing]
---

## Unit data

designation:: 196th Attack Squadron
parent_command:: 163d Attack Wing (163 AW), California Air National Guard; deployed under AFCENT / USCENTCOM
home_station:: March ARB, California (deployed elements in the CENTCOM AOR)
aircraft:: [[Platform - MQ-9 Reaper]]
typical_mission:: Remotely piloted ISR and reconnaissance (FMV + SIGINT)

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

## Notes

Named originator on the D12 Iraq May 2022 MISREP. An Air National Guard MQ-9 unit flying ISR/RECON taskings in support of Operation Inherent Resolve, with FMV exploited by DGS 1.
