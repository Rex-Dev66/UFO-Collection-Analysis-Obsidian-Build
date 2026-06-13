---
title: Platform - MQ-9 Reaper
tags: [platform, platform/mq-9]
type: platform
aliases: [MQ-9, Reaper, Predator B, RPA]
---

## Specifications

type:: Medium-altitude, long-endurance (MALE) remotely piloted aircraft
role:: ISR, strike, target development, full-motion video (FMV) and SIGINT collection
service:: U.S. Air Force and Air National Guard attack/reconnaissance squadrons
primary_sensor:: MTS-B EO/IR full-motion video turret; SIGINT payloads (AHv2 / ANDAS4 referenced in reports)
typical_mission:: ISR, RECON, XCAS, target development; endurance commonly 18+ hours

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

## Notes

The MQ-9 is the most common ISR observer in the CENTCOM UAP corpus. Its EO/IR turret streams full-motion video exploited by a Distributed Ground Station (DGS), so UAP observations from this platform are screener-mediated rather than direct eyewitness. Long loiter time plus continuous FMV means transient objects (birds, balloons, small UAS, debris) frequently cross the field of view, which is reflected in the high rate of "possible bird" and "possible balloon" attributions in Reaper-originated reports.

## Related

- Units: [[Unit - 432 AEW]] | [[Unit - 196 ATKS]]
- Sensor: [[Sensor - EO IR]]
