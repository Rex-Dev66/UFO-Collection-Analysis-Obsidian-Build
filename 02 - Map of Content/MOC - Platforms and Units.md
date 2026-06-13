---
title: MOC - Platforms and Units
tags: [moc]
type: moc
---

## All platforms

```dataview
LIST
FROM "06 - Platforms and Units"
WHERE startswith(file.name, "Platform")
SORT file.name ASC
```

## All units

```dataview
LIST
FROM "06 - Platforms and Units"
WHERE startswith(file.name, "Unit")
SORT file.name ASC
```

## Incidents per platform

```dataview
TABLE WITHOUT ID
  platform AS "Platform",
  length(rows) AS "Count"
FROM "03 - Incidents"
GROUP BY platform
SORT length(rows) DESC
```

## Incidents per unit

```dataview
TABLE WITHOUT ID
  unit AS "Unit",
  length(rows) AS "Count"
FROM "03 - Incidents"
GROUP BY unit
SORT length(rows) DESC
```
