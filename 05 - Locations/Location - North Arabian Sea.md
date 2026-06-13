---
title: Location - North Arabian Sea
tags: [location, aor/centcom]
type: location
aliases: [NAS, Working Area 21440]
---

## Geography

country:: International waters (south of Iran/Pakistan, east of Oman, north of Arabian Sea proper)
region:: Indian Ocean / Northern Indian Ocean
aor:: centcom
mgrs_zone:: 41R, 41Q, 42R, 42Q

## Significance

Operating area for U.S. Navy MH-60R squadrons supporting carrier strike group operations and Combined Maritime Forces. Adjacent to Iranian coast and IRGC Navy operating areas. Within range of Iranian small unmanned aerial systems and surface-to-air-launched UAS.

## Incidents at this location

```dataview
TABLE
  date_event AS "Date",
  platform AS "Platform",
  shape AS "Shape",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(location, this.file.link)
SORT date_event ASC
```

## Related

- Patterns: [[Thesis - 2020 Arabian Gulf Cluster]]
- Adjacent: [[Location - Arabian Gulf]] | [[Location - Strait of Hormuz]] | [[Location - Gulf of Aden]]
