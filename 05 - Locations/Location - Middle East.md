---
title: Location - Middle East
tags: [location, aor/centcom]
type: location
---

## Geography

region:: Generic regional descriptor used in some source documents
aor:: centcom

> [!NOTE]
> Some source MISREPs use "Middle East" as the location descriptor without further specificity. When location can be inferred from MGRS or other context, prefer the specific location note.

## Incidents

```dataview
TABLE
  date_event AS "Date",
  platform AS "Platform",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(location, this.file.link)
SORT date_event ASC
```
