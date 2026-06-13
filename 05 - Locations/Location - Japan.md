---
title: Location - Japan
tags: [location, aor/indopacom]
type: location
---

## Geography

country:: Japan
region:: Northeast Asia
aor:: indopacom

## Significance

Treaty ally. Hosts large U.S. military presence (USFJ): Yokosuka, Atsugi, Misawa, Iwakuni, Okinawa. Forward base for INDOPACOM rotations and carrier strike group operations.

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
