---
title: Unit - CTG 67.1
tags: [unit]
type: unit
aliases: [Commander Task Group 67.1]
---

## Unit data

designation:: Commander, Task Group 67.1
parent_command:: Commander, Task Force 67 / U.S. Sixth Fleet
typical_mission:: P-8A patrol and reconnaissance in the Mediterranean / European theater
aircraft:: [[Platform - P-8A Poseidon]]

## Incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(unit, this.file.link)
SORT date_event DESC
```
