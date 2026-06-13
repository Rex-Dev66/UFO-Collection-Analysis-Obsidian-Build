---
title: Unit - 77 EFS
tags: [unit, aor/centcom, platform/f-16]
type: unit
aliases: [77th Expeditionary Fighter Squadron, 77 EFS]
---

## Unit data

designation:: 77th Expeditionary Fighter Squadron (inferred from "77 EFS" reporting designator)
parent_command:: USAF / AFCENT (USCENTCOM air component, expeditionary deployment)
home_station:: deployed expeditionary location (redacted in the record)
aircraft:: [[Platform - F-16 Fighting Falcon]]
typical_mission:: DCA (Defensive Counter-Air) and OCA; alert intercept of unknown contacts under AWACS control

## Incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  platform AS "Platform",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(unit, this.file.link)
SORT date_event DESC
```

## Notes

Reporting unit for the 2020-10-27 Range Fouler incident in which an F-16 obtained a stable radar lock and target-pod video on two IR-significant objects, one circling the other, and received active noise jamming before the objects disappeared in 1/30 second. The DCA mission profile, AWACS-directed intercept (KINGPIN), and target-pod employment are all consistent with an F-16 fighter squadron.

Squadron number and deployment location are inferred from the report's "77 EFS" designator; specific basing is redacted.
