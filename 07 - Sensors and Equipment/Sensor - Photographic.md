---
title: Sensor - Photographic
tags: [sensor]
type: sensor
aliases: [handheld camera, phone camera, long exposure]
---

## Specifications

type:: Consumer/handheld still camera or smartphone
band:: Visible
host_platform:: [[Platform - Ground Observer]]
manufacturer:: various

## Detection characteristics

Handheld photography is the only "instrument" capture in the tranche 3 domestic cases, and it is a weak one. Night sightings were shot at long exposure without a tripod, producing blurred, smeared light blobs. This is important for assessment: long-exposure motion blur and out-of-focus point sources can manufacture "orb"-like artifacts, so photographic stills from these cases corroborate that *something luminous* was present but rarely resolve its shape, size, or distance. No calibrated radar, EO/IR, or ADS-B-correlated imagery accompanies the domestic orb cases.

## Incidents using this sensor

```dataview
TABLE
  date_event AS "Date",
  location AS "Location",
  status AS "Status"
FROM "03 - Incidents"
WHERE contains(sensor, this.file.link)
SORT date_event DESC
```
