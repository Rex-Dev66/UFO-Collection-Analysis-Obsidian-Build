---
title: MOC - Incidents by Location
tags: [moc]
type: moc
---

## All locations

```dataview
LIST
FROM "04 - Locations"
SORT file.name ASC
```

## Incidents per location

```dataview
TABLE WITHOUT ID
  location AS "Location",
  length(rows) AS "Count"
FROM "02 - Incidents"
GROUP BY location
SORT length(rows) DESC
```

## CENTCOM incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  platform AS "Platform",
  status AS "Status"
FROM "02 - Incidents"
WHERE aor = "centcom"
SORT date_event ASC
```

## INDOPACOM incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  status AS "Status"
FROM "02 - Incidents"
WHERE aor = "indopacom"
SORT date_event ASC
```

## All other AORs

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  aor AS "AOR",
  status AS "Status"
FROM "02 - Incidents"
WHERE aor != "centcom" AND aor != "indopacom"
SORT date_event ASC
```
