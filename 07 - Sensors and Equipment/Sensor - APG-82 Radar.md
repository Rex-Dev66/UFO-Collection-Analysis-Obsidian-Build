---
title: Sensor - APG-82 Radar
tags: [sensor, sensor/radar-apg82]
type: sensor
aliases: [APG-82, APG-82(V)1]
---

## Specifications

type:: Active Electronically Scanned Array (AESA) fire-control radar
band:: X-band (8.8 to 9.9 GHz observed in D19)
host_platform:: [[Platform - F-15E Strike Eagle]]
manufacturer:: Raytheon

## Detection characteristics

The APG-82 provides air-to-air and air-to-ground modes including synthetic aperture radar mapping, ground moving-target indicator, and air-to-air search and track. It is susceptible to electronic attack on its operating frequencies; the 21 Feb 2023 [[Incident - 2023-02-21 Shaddadi F-15E]] documented 3 minutes of MFT (multi-function threat) radar jamming assessed as Turkish ground-based X-band emission.

When UAPs do not return radar (as in the D19 incident), the absence of radar return is itself a data point. It can indicate a low radar cross-section (small physical size, stealth-shaping, or radar-absorbent material), an angle that puts the object outside the radar beam, or that the object simply does not present the kind of return the radar is tuned to discriminate.

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
