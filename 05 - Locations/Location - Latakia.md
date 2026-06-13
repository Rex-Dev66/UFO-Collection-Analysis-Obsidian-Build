---
title: Location - Latakia
tags: [location, aor/centcom]
type: location
---

## Geography

country:: Syria (Latakia Governorate, northwest coast)
region:: Levant / Eastern Mediterranean coast
aor:: centcom

## Significance

==Russian Khmeimim Air Base== is located near Latakia; this is the primary Russian military air operations hub in Syria. Russian Navy logistics also stage from Tartus to the south. Latakia is the geographic anchor for the Russian Mediterranean military footprint in support of Syrian government operations.

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
