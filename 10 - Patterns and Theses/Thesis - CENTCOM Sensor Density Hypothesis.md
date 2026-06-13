---
title: Thesis - CENTCOM Sensor Density Hypothesis
tags: [thesis]
type: thesis
status: provisionally-supported
confidence: high
---

## Hypothesis

UAP reporting density in this collection follows U.S. military sensor and mission density, not underlying UAP density. The fact that ==CENTCOM dominates the reporting is a reflection of where the U.S. has eyes and reporting infrastructure==, not where unusual aerial objects preferentially appear.

## Reasoning

1. CENTCOM hosts the highest-density U.S. military ISR coverage globally, owing to ~25 years of continuous operations.
2. Mandatory reporting under Navy and joint guidance produces a denominator (observation hours) far higher in CENTCOM than in other AORs.
3. As INDOPACOM reporting scaled up in 2023-2025, INDOPACOM share of the corpus grew, consistent with the hypothesis (more sensors there, more reports from there).
4. The collection contains zero reports from EUCOM proper (excluding the Mediterranean coast), zero from SOUTHCOM, and very few from AFRICOM, despite UAP observations being reported globally in non-government channels.

## Supporting incidents

```dataview
LIST
FROM "03 - Incidents"
WHERE contains(supports_theses, this.file.link)
```

## Disconfirming evidence

- If a future release contains a large NORTHCOM or SOUTHCOM cluster without a corresponding expansion of sensor coverage, the thesis would be weakened.

## Confidence

confidence:: high
basis:: Structural argument about sampling bias; supported by the asymmetric distribution observed in the corpus.

## Implication

When evaluating any AARO-era public statistics about UAP geography, ==always control for sensor density==. The reported geography is the sensor geography.

## Related

- [[Thesis - 2020 Arabian Gulf Cluster]]
- [[Location - Arabian Gulf]]
- [[Location - INDOPACOM AOR]]
