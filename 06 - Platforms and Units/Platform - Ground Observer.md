---
title: Platform - Ground Observer
tags: [platform, platform/ground-observer]
type: platform
aliases: [Civilian Witness, Witness on Ground]
---

## Specifications

type:: Human witness on the ground
role:: Visual observation only (typically no instruments)
service:: n/a
primary_sensor:: Mark I Eyeball

## Incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(platform, this.file.link)
SORT date_event DESC
```

## Notes

Ground observer reports are subject to all known eyewitness reliability constraints: distance and altitude estimation errors, duration overestimation for brief events, shape interpretation biases, and post-event memory consolidation effects. Documented witness disagreement (as in the LiDAR Convoy 2023 incident, where two witnesses gave materially different descriptions) is normal, not exceptional.
