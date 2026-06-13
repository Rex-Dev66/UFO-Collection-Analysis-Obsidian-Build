---
title: Platform - Boeing 747SP Civilian
tags: [platform, platform/civilian-aviation]
type: platform
aliases: [747SP]
---

## Specifications

type:: Long-range wide-body commercial airliner
role:: Civilian airline service
service:: Various (Tajik Air in the 1994 Kazakhstan incident)
primary_sensor:: weather radar + cockpit visual
typical_mission:: Scheduled passenger or cargo

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

Cruise altitude FL350-FL410. Crews include 2-3 trained pilots with extensive flight hours. Civilian aviation reports of UAPs benefit from highly trained observers but suffer from weather radar limitations (designed for weather, not air-to-air contacts).
