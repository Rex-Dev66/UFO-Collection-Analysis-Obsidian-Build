---
title: MOC - Patterns and Theses
tags: [moc]
type: moc
---

> [!NOTE]
> Requires Dataview plugin. See [[SETUP FIRST]] if these tables show as raw code.

## Active theses

```dataview
TABLE
  status AS "Status",
  confidence AS "Confidence"
FROM "09 - Patterns and Theses"
SORT confidence DESC
```

## By status

```dataview
TABLE WITHOUT ID
  status AS "Status",
  length(rows) AS "Count"
FROM "09 - Patterns and Theses"
WHERE status
GROUP BY status
```

## High-confidence patterns

```dataview
LIST
FROM "09 - Patterns and Theses"
WHERE confidence = "high"
```

## Incidents per thesis (which theses are most supported)

```dataview
TABLE WITHOUT ID
  supports_theses AS "Thesis",
  length(rows) AS "Supporting Incidents"
FROM "02 - Incidents"
WHERE supports_theses
GROUP BY supports_theses
SORT length(rows) DESC
```
