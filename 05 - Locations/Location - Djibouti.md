---
title: Location - Djibouti
tags: [location, aor/africom]
type: location
---

## Geography

country:: Djibouti
region:: Horn of Africa
aor:: africom

## Significance

Hosts Camp Lemonnier (largest U.S. military base in Africa), plus French, Japanese, and Chinese military installations. Dense airspace. Strategic position at the entrance to the Red Sea (Bab al-Mandeb).

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

- Adjacent: [[Location - Gulf of Aden]]
