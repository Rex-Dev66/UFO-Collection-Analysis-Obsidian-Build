---
title: Platform - Apollo CSM
tags: [platform, platform/apollo-csm]
type: platform
aliases: [CSM, Command and Service Module, Yankee Clipper, America]
---

## Specifications

type:: Crewed lunar spacecraft (Command Module + Service Module)
role:: Translunar, lunar orbital, transearth
service:: NASA
typical_mission:: Apollo lunar landing missions 11 through 17

## Incidents reported from this platform

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

Observation environment is unique: vacuum, no atmospheric scattering, deep black sky, no atmospheric refraction. Visual phenomena that look anomalous to terrestrial intuition (cosmic ray phosphenes, debris field illumination, lunar surface flashes from meteoroid impacts) are routine in this environment.
