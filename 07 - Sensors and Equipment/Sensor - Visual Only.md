---
title: Sensor - Visual Only
tags: [sensor, sensor/visual-only]
type: sensor
aliases: [Mark I Eyeball, Visual]
---

## Specifications

type:: Unaided human visual observation
host_platform:: Any platform with a window

## Detection characteristics

Most reliable for stable, well-lit, high-contrast targets at known ranges. Least reliable for brief, low-contrast, unknown-range events. Subject to all standard eyewitness reliability constraints documented in the cognitive psychology and aviation safety literature.

When visual observation is the only sensor (no radar, no EO/IR record), an observation can only be classified as "unresolved." It cannot be elevated to "anomalous" by pilot credibility alone, no matter how well-trained the pilot.

## Incidents using this sensor

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(sensor, this.file.link)
SORT date_event DESC
```
