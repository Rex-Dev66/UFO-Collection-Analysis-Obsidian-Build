---
title: Location - CONUS LiDAR Test Site
tags: [location, aor/northcom]
type: location
aliases: [LiDAR Test Site]
---

## Geography

country:: United States
region:: Continental United States (specific location redacted in source)
aor:: northcom

## Significance

Location of the September 2023 LiDAR test convoy incident. Specific location redacted in [[Source - FBI Serial 4 Redacted]] and [[Source - FBI Serial 5 Redacted]]. Restricted airspace had been arranged for drone testing on the day of the encounter, which is one reason Witness A found the observed object notable.

## Incidents

```dataview
TABLE
  date_event AS "Date",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(location, this.file.link)
SORT date_event ASC
```

## Notes

The FBI interview reports do not name the location. Possible candidates include any of the established U.S. LiDAR / drone test ranges (e.g., White Sands area, various DoD-restricted ranges in the western states). The witness travel pattern (driving south at 7:30 AM with sun in east, good visibility, multiple test sites, hotel stay) suggests a contractor-style remote test campaign.
