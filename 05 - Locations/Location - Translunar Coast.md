---
title: Location - Translunar Coast
tags: [location, aor/space]
type: location
---

## Geography

region:: Cislunar space (Earth-to-Moon transit)
aor:: space

## Significance

Cislunar coast phase of Apollo missions, between Earth departure and lunar orbit insertion. Free-fall, vacuum, no atmospheric scattering. Multiple Apollo-era observations occurred during this phase.

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
