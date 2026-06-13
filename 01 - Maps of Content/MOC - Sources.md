---
title: MOC - Sources
tags: [moc]
type: moc
---

> [!NOTE]
> Requires Dataview plugin. See [[SETUP FIRST]] if these tables show as raw code.

## All sources

```dataview
TABLE
  release_date AS "Released",
  mdr_number AS "MDR"
FROM "03 - Sources"
SORT release_date DESC
```

## By MDR batch

```dataview
TABLE WITHOUT ID
  mdr_number AS "MDR",
  length(rows) AS "Count"
FROM "03 - Sources"
WHERE mdr_number
GROUP BY mdr_number
SORT length(rows) DESC
```

## DOW sources

```dataview
LIST
FROM "03 - Sources"
WHERE contains(file.tags, "#agency/dow")
SORT file.name ASC
```

## NASA sources

```dataview
LIST
FROM "03 - Sources"
WHERE contains(file.tags, "#agency/nasa")
SORT file.name ASC
```

## FBI sources

```dataview
LIST
FROM "03 - Sources"
WHERE contains(file.tags, "#agency/fbi")
SORT file.name ASC
```

## State Department sources

```dataview
LIST
FROM "03 - Sources"
WHERE contains(file.tags, "#agency/state")
SORT file.name ASC
```

## CIA sources

```dataview
LIST
FROM "03 - Sources"
WHERE contains(file.tags, "#agency/cia")
SORT file.name ASC
```

## ICA / AARO analysis

```dataview
LIST
FROM "03 - Sources"
WHERE contains(file.tags, "#agency/ica") OR contains(file.tags, "#agency/aaro")
SORT file.name ASC
```

## Historical service & Congressional sources (Army / Navy / USAF / USG)

```dataview
LIST
FROM "03 - Sources"
WHERE contains(file.tags, "#agency/army") OR contains(file.tags, "#agency/navy") OR contains(file.tags, "#agency/usaf") OR contains(file.tags, "#agency/usg")
SORT file.name ASC
```

## PURSUE Release 03 (tranche 3) sources

```dataview
LIST
FROM "03 - Sources"
WHERE contains(file.tags, "#release/pursue")
SORT file.name ASC
```
