---
title: Unit - 172 ATKS
tags: [unit]
type: unit
aliases: [172nd Attack Squadron]
---

## Unit data

designation:: 172nd Attack Squadron
parent_command:: USAF
typical_mission:: ISR, MQ-9 Reaper or similar unmanned platform operations
aircraft:: unmanned ISR platform (inferred from "Other" crew position in Range Fouler)

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

Range Fouler form for D44 listed crew position as "Other," which is typical of MQ-9 sensor operators (who are not pilots in the traditional sense).
