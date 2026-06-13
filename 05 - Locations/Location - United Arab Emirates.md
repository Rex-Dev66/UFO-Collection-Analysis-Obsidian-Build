---
title: Location - United Arab Emirates
tags: [location, aor/centcom]
type: location
aliases: [UAE]
---

## Geography

country:: United Arab Emirates
region:: Arabian Peninsula
aor:: centcom

## Significance

Hosts Al Dhafra Air Base, a major U.S. and coalition airbase. Active partner in CENTCOM operations.

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
