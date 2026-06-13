---
title: Phenom - No Radar Return
tags: [phenom, phenom/no-radar-return]
type: phenom
---

## Definition

The observing platform's radar does not return contact on the visually or EO/IR-detected object, even when the radar is operating normally and the object is within range and angular coverage.

## Incidents

```dataview
LIST
FROM "03 - Incidents"
WHERE contains(file.tags, "#phenom/no-radar-return") OR radar_return = "no"
SORT date_event DESC
```

## Conventional candidates

- Low radar cross-section (small physical size; consider drones smaller than ~30cm)
- Radar-absorbent or radar-translucent materials (mylar balloons can be intermittent; soft-bodied objects are weak returns)
- Object outside radar beam at moment of observation (high look-down angles or radar pointing elsewhere)
- Object motion below or near minimum detectable velocity for the radar mode in use
- Object at altitude that puts it outside operating envelope of the specific radar mode

## Analytical note

Absence of radar return alone is not evidence of an exotic object. It is a useful constraint on size, material, and motion. Combined with other unusual sensor behavior, it becomes more informative.
