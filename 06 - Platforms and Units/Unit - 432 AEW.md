---
title: Unit - 432 AEW
tags: [unit, aor/centcom]
type: unit
aliases: [432d Air Expeditionary Wing, 432 AEW, Hunters]
---

## Unit data

designation:: 432d Wing / 432d Air Expeditionary Wing ("Hunters")
parent_command:: Air Combat Command; deployed under AFCENT / USCENTCOM
home_station:: Creech AFB, Nevada (deployed elements in the CENTCOM AOR)
aircraft:: [[Platform - MQ-9 Reaper]]
typical_mission:: Remotely piloted ISR and strike (FMV + SIGINT)

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

## Notes

Appears as the POC wing on MQ-9 MISREPs in the CENTCOM corpus where the originating squadron is redacted. Operations are coordinated through the 609th Air Operations Center (CAOC) and full-motion video is exploited by a Distributed Ground Station.
