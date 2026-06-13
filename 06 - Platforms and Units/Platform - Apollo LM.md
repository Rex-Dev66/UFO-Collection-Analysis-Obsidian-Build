---
title: Platform - Apollo LM
tags: [platform, platform/apollo-lm]
type: platform
aliases: [Apollo LM, Lunar Module, LEM]
---

## Specifications

type:: two-stage crewed lunar lander (Grumman)
role:: lunar descent, surface operations base, and ascent to lunar orbit
service:: NASA
primary_sensor:: crew visual observation; rendezvous radar; Alignment Optical Telescope (AOT)
secondary_sensors:: tracking light, optical sights
typical_mission:: ferry two crew between lunar orbit and the surface (Apollo 12 "Intrepid," Apollo 17 "Challenger")

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

The LM appears in the NASA transcripts alongside the [[Platform - Apollo CSM]]. On Apollo 12, LMP Alan Bean's "particles of light" report was made looking out the LM Alignment Optical Telescope (AOT) in the dark quadrant, and a tracking-light visibility discrepancy resolved to an observation issue rather than a hardware failure. Most LM-associated observations in this collection were identified in real time by the crew or Capcom.
