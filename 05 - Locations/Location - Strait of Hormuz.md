---
title: Location - Strait of Hormuz
tags: [location, aor/centcom]
type: location
aliases: [SOH]
---

## Geography

country:: International waters between Iran and Oman/UAE
region:: Connects [[Location - Persian Gulf]] to [[Location - Gulf of Aden]] via Arabian Sea
aor:: centcom
coordinates:: ~26.5 N, 56.5 E

## Significance

==Most strategically important maritime chokepoint== in the world for oil shipping. Persistent U.S. and coalition naval presence. Site of repeated Iranian small-boat and UAS incidents. Heavy ISR overwatch.

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
