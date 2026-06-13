---
title: Location - Iran
tags: [location, aor/centcom]
type: location
---

## Geography

country:: Islamic Republic of Iran
region:: Middle East
aor:: centcom

## Significance

Adjacent to multiple high-density UAP reporting areas (Persian Gulf, Strait of Hormuz, North Arabian Sea). Iranian UAS development matured significantly in the late 2010s and 2020s; many small Iranian unmanned platforms are candidate explanations for observations in the immediate area.

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

## Related

- Adjacent: [[Location - Persian Gulf]] | [[Location - Strait of Hormuz]] | [[Location - North Arabian Sea]]
- Pattern: [[Thesis - 2020 Arabian Gulf Cluster]]
