---
title: Location - Kazakhstan
tags: [location, aor/indopacom]
type: location
---

## Geography

country:: Republic of Kazakhstan
region:: Central Asia
aor:: indopacom (formerly transitional post-Soviet)

## Significance

Largest landlocked country. Sparsely populated; large unmonitored airspace, especially in 1994. Hosts Baikonur Cosmodrome (Russian-leased; major space launch facility historically). Adjacent to multiple post-Soviet successor states with chaotic 1990s airspace governance.

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

- Adjacent: post-Soviet Central Asia (Tajikistan, Uzbekistan, Kyrgyzstan)
- Notable: Baikonur Cosmodrome upper-stage debris regularly transits Kazakh airspace
