---
title: Location - Persian Gulf
tags: [location, aor/centcom]
type: location
aliases: [The Gulf]
---

## Geography

country:: International waters (bordered by Iran, Saudi Arabia, UAE, Qatar, Bahrain, Kuwait, Iraq)
region:: Middle East
aor:: centcom
coordinates:: 24-30 N, 48-57 E

> [!NOTE]
> "Persian Gulf" and "Arabian Gulf" refer to the same body of water; nomenclature varies by political context. The vault uses both as appropriate to the source document.

## Significance

Same operational significance as [[Location - Arabian Gulf]]. Heavy U.S. Fifth Fleet presence, persistent ISR coverage, Iranian operating areas adjacent.

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

- See also: [[Location - Arabian Gulf]] | [[Location - Strait of Hormuz]]
