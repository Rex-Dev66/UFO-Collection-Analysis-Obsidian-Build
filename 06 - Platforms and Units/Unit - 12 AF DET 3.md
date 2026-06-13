---
title: Unit - 12 AF DET 3
tags: [unit]
type: unit
aliases: [12 AF / DET 3, PAROC]
---

## Unit data

designation:: 12th Air Force, Detachment 3
parent_command:: PACAF or AFSOC (PAROC team within)
typical_mission:: Intel data analysis (PAROC = Production, Analysis, Reporting Operations Center)
function:: Coordinates UAP tearline reviews from INDOPACOM sources

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

Named in [[Source - DOW-UAP-D50 INDOPACOM Email April 2025]] as the originating unit for the April 2025 INDOPACOM tearline approvals.
