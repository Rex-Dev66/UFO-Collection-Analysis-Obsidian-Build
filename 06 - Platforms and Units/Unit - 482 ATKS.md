---
title: Unit - 482 ATKS
tags: [unit, aor/centcom]
type: unit
aliases: [482nd Attack Squadron, 482 ATKS]
---

## Unit data

designation:: 482nd Attack Squadron (inferred from "482 ATKS" reporting designator)
parent_command:: USAF / AFCENT (USCENTCOM air component)
home_station:: unknown from the record
aircraft:: [[Platform - MQ-9 Reaper]] (inferred from ANDAS4 / AN/DAS-4 MX-class EO/IR ball and long-endurance AREC tasking)
typical_mission:: AREC (Armed Reconnaissance) and ISR over CENTCOM maritime AOR; pattern-of-life and UAS-activity monitoring against Iranian naval forces

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

This unit is the reporting squadron for the cluster of 2020 Persian Gulf / Strait of Hormuz / Gulf of Oman ISR observations (D60-D65). Mission narratives describe long-endurance sorties (one mission ran ~21 hours), MX-class EO/IR sensor (ANDAS4) and AH/GMESH avionics, and explicit tasking to monitor Iranian unmanned aerial system (UAS) and IRGC-N / IRINS naval activity. The "ATKS" designator and the unmanned, long-endurance sensor fit point to an MQ-9 Reaper attack squadron rather than a crewed platform.

Designation and home station are inferred; the released documents redact most unit identifying detail. Confirm against the source PDFs when available.
