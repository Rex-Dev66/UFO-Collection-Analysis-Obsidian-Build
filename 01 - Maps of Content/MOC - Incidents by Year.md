---
title: MOC - Incidents by Year
tags: [moc]
type: moc
---

> [!NOTE]
> Requires Dataview plugin. See [[SETUP FIRST]] if these tables show as raw code.

## All incidents, by date

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  platform AS "Platform",
  status AS "Status"
FROM "02 - Incidents"
SORT date_event ASC
```

## By year (count)

```dataview
TABLE WITHOUT ID
  Year,
  length(rows) AS "Count"
FROM "02 - Incidents"
FLATTEN string(date_event) AS DateStr
GROUP BY substring(DateStr, 0, 4) AS Year
SORT Year ASC
```

## By status

```dataview
TABLE WITHOUT ID
  status AS "Status",
  length(rows) AS "Count"
FROM "02 - Incidents"
GROUP BY status
SORT length(rows) DESC
```

## By AOR

```dataview
TABLE WITHOUT ID
  aor AS "AOR",
  length(rows) AS "Count"
FROM "02 - Incidents"
GROUP BY aor
SORT length(rows) DESC
```

## Unresolved only

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  platform AS "Platform"
FROM "02 - Incidents"
WHERE status = "unresolved"
SORT date_event ASC
```

## Assessed conventional

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  platform AS "Platform"
FROM "02 - Incidents"
WHERE status = "assessed-conventional"
SORT date_event ASC
```
