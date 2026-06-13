---
title: Location - Syria
tags: [location, aor/centcom]
type: location
---

## Geography

country:: Syrian Arab Republic
region:: Levant
aor:: centcom

## Significance

Active conflict zone since 2011. Multiple foreign air forces operate in or over Syrian airspace: Russian, Turkish, Israeli, US/coalition (OIR), Syrian government, occasional Iranian. Eastern Syria (around [[Location - Shaddadi]]) is the main U.S. operating area. The skies are dense with conventional aircraft, drones, and surveillance balloons; attribution of any observation is challenging.

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

- Adjacent: [[Location - Shaddadi]] | [[Location - Eastern Mediterranean]] | [[Location - Iraq]]
