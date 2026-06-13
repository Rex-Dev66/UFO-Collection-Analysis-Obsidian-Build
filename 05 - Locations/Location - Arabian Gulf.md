---
title: Location - Arabian Gulf
tags: [location, aor/centcom]
type: location
aliases: [Persian Gulf, AG]
---

## Geography

country:: International waters (bordered by Iran, Saudi Arabia, UAE, Qatar, Bahrain, Kuwait, Iraq)
region:: Middle East
aor:: centcom
coordinates:: ~26-30 N, 49-57 E
mgrs_zone:: 34S, 35S, 39R, 39S, 40R, 40S

## Significance

The Arabian Gulf is the single highest-density UAP reporting region in this collection. It hosts persistent U.S. Navy carrier presence (Fifth Fleet headquartered in Bahrain), continuous ISR coverage, U.S. Air Force operations from Al Udeid (Qatar), Al Dhafra (UAE), and multiple coalition partner operations. It is also adjacent to Iranian operating areas including the IRGC Navy.

Bottom line: high ISR density plus active foreign UAS development plus narrow strategic waterway equals an environment ==maximally biased toward UAP reporting==, independent of UAP density.

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

- Patterns: [[Thesis - 2020 Arabian Gulf Cluster]] | [[Thesis - CENTCOM Sensor Density Hypothesis]]
- Adjacent locations: [[Location - Strait of Hormuz]] | [[Location - Persian Gulf]] | [[Location - North Arabian Sea]] | [[Location - Gulf of Aden]]
