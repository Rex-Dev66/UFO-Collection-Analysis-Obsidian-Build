---
title: Platform - P-8A Poseidon
tags: [platform, platform/p-8a]
type: platform
aliases: [P-8, P-8A, Poseidon]
---

## Specifications

type:: Maritime patrol and anti-submarine warfare aircraft (Boeing 737 derivative)
role:: ASW, ASUW, ISR, maritime patrol
service:: U.S. Navy
primary_sensor:: APY-10 radar, MX-20HD EO/IR, acoustic sonobuoy suite
typical_mission:: Maritime patrol, KCTG monitoring, ASW

## Incidents reported from this platform

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  shape AS "Shape",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(platform, this.file.link)
SORT date_event DESC
```
