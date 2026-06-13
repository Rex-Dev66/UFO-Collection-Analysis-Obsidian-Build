---
title: Location - Greece
tags: [location, aor/eucom]
type: location
---

## Geography

country:: Hellenic Republic
region:: Eastern Mediterranean / Southern Europe
aor:: eucom

## Significance

NATO ally. Hosts U.S. forward operating capability at NSA Souda Bay, Crete. Greek airspace is the EUCOM-adjacent buffer for Eastern Mediterranean operations.

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
