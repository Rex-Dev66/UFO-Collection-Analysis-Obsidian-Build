---
title: Location - Eastern Mediterranean
tags: [location, aor/centcom, aor/eucom]
type: location
aliases: [Eastern Med, EMED]
---

## Geography

country:: International waters bordered by Syria, Lebanon, Israel, Cyprus, Turkey
region:: Mediterranean
aor:: centcom and eucom seam
mgrs_zone:: 36S, 37S

## Significance

Historical and contemporary area of operations for U.S. Sixth Fleet and the Russian Mediterranean Squadron. Hosted [[Russian KCTG|Russian Kuznetsov Carrier Task Group]] deployment late 2016 in support of Russian Syria operations. Routine U.S. P-8A patrols monitor Russian and Syrian naval activity.

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

- Adjacent: [[Location - Latakia]]
- Patterns: [[Thesis - Russian Activity Drives Mediterranean Observations]]
