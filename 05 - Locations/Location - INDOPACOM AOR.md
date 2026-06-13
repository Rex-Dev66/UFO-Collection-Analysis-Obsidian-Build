---
title: Location - INDOPACOM AOR
tags: [location, aor/indopacom]
type: location
aliases: [Indo-Pacific, USINDOPACOM]
---

## Geography

region:: Indo-Pacific (the largest U.S. combatant command AOR by area)
aor:: indopacom

## Significance

Spans approximately half the earth's surface, including East China Sea, South China Sea, Philippine Sea, Japan, Korea, Australia. Increasing UAP reporting volume as part of the 2023-2025 expansion of the centralized AARO collection pipeline beyond CENTCOM.

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

- Adjacent: [[Location - East China Sea]] | [[Location - Papua New Guinea]]
