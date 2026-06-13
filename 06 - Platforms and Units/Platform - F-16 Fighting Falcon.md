---
title: Platform - F-16 Fighting Falcon
tags: [platform, platform/f-16]
type: platform
aliases: [F-16, Fighting Falcon, Viper]
---

## Specifications

type:: single-engine multirole fighter
role:: DCA, OCA, strike, SEAD
service:: USAF (and numerous allied air forces)
primary_sensor:: fire-control radar (AN/APG-68 or AN/APG-83 SABR on later blocks)
secondary_sensors:: targeting pod (AN/AAQ-33 Sniper or AN/AAQ-28 Litening) with EO/IR FLIR
typical_mission:: air defense alert, counter-air, and precision strike

## Incidents reported from this platform

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  shape AS "Shape",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(platform, this.file.link)
SORT date_event DESC
```

## Notes

In the 2020-10-27 Range Fouler incident, an F-16 from [[Unit - 77 EFS]] obtained a stable radar trackfile and targeting-pod video on two objects and received active noise jamming (indicated by two chevrons on the radar display) before the objects disappeared within a single video frame. The case illustrates the F-16's relevant sensor suite for UAP work: a fire-control radar that registers electronic attack, plus a targeting pod that records IR-significant contacts.

Platform attribution in that incident is inferred from the 77 EFS DCA tasking; the report itself redacts the airframe.
