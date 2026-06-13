---
title: Unit - AFCENT
tags: [unit, aor/centcom]
type: unit
aliases: [AFCENT, U.S. Air Forces Central, Ninth Air Force, USAFCENT]
---

## Unit data

designation:: U.S. Air Forces Central (AFCENT) / Ninth Air Force (Air Forces Central)
parent_command:: USCENTCOM (air component command)
home_station:: Shaw AFB, South Carolina (component HQ); forward elements at Al Udeid AB, Qatar
aircraft:: command echelon, not a flying unit (tasks subordinate wings and expeditionary squadrons)
typical_mission:: MAJCOM-level command and control of USAF air operations across the CENTCOM AOR

## Incidents

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  platform AS "Platform",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(unit, this.file.link)
SORT date_event DESC
```

## Notes

AFCENT is the USAF air component of USCENTCOM, not a squadron. It appears in the record as the tasking MAJCOM for ISR missions whose specific reporting squadron is redacted (e.g. the 2020 Arabian Gulf D3 4-UAP observation). Where an incident lists "AFCENT" as the unit, treat it as the command echelon, the actual flying squadron is unstated in the released document.
