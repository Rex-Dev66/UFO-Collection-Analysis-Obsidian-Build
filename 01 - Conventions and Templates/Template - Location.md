---
title: Location - Name
tags: [location, aor/centcom]
type: location
aliases: []
---

## Geography

country:: 
region:: 
aor:: 
coordinates:: 
mgrs_zone:: 

## Significance

Why is this location operationally important? What U.S. military presence, ISR coverage, or geopolitical activity occurs here? Any pre-existing UAP reporting history?

## Incidents at this location

```dataview
TABLE
  date_event AS "Date",
  platform AS "Platform",
  shape AS "Shape",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(location, this.file.link)
SORT date_event ASC
```

## Related

- Patterns: 
- Adjacent locations: 
