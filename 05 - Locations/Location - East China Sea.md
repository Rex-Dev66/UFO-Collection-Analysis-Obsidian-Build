---
title: Location - East China Sea
tags: [location, aor/indopacom]
type: location
aliases: [ECS]
---

## Geography

country:: International waters bordered by China, Taiwan, Japan, Korea
region:: Northeast Asia
aor:: indopacom

## Significance

Strategically critical maritime area; site of regular PLA (People's Liberation Army) air and naval activity, Japanese ADIZ overflights, and U.S. freedom-of-navigation operations. Dense aerial activity makes UAP attribution complex.

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
