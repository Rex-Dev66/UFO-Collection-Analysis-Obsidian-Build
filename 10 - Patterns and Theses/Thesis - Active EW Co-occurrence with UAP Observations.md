---
title: Thesis - Active EW Co-occurrence with UAP Observations
tags: [thesis]
type: thesis
status: open
confidence: moderate
---

## Hypothesis

==Multiple incidents in the collection show electromagnetic interference, radar jamming, or C2 link loss in temporal proximity to UAP observations== from the same platform on the same sortie. The pattern is consistent enough across separate events to warrant treatment as a recurring signature rather than coincidence.

## Reasoning

1. [[Incident - 2020-10 D58 Range Fouler]] (F-16, DCA, Oct 2020): two metallic objects observed, ==noise jamming received by F-16 radar simultaneously with the visual contact==, objects then disappeared in 1/30 second.
2. [[Incident - 2020-09 Strait of Hormuz D62]] (MQ-9, AREC, Sep 2020): two LOST LINK EMI events (11 min and 27 min) plus one UAP observation, all during the same 21-hour mission. Iranian air defense actively contesting the airspace.
3. [[Incident - 2023-02-21 Shaddadi F-15E]] (F-15E, DCA, Feb 2023): three minutes of MFT radar jamming on APG-82 ==one minute before== the visual sighting of three UAPs at FL240. The jamming was assessed in the same document as Turkish ground-based X-band, not UAP-caused, but the temporal co-occurrence is notable.

## Supporting incidents

```dataview
LIST
FROM "03 - Incidents"
WHERE contains(supports_theses, this.file.link)
```

## Disconfirming evidence

- The Shaddadi case has an explicit non-UAP attribution for the EMI (Turkish ground jammer).
- The D62 jamming is plausibly attributable to Iranian electronic warfare directed at the U.S. MQ-9, not to the UAP itself.
- Many UAP observations in the collection have ==no== associated EMI; the co-occurrence pattern is not universal.

## Two distinct interpretations

==(A) Coincidental co-location==: U.S. ISR is most active where adversaries deploy electronic warfare, and adversaries also deploy unmanned systems. Both UAPs and EW co-occur because they share an operating environment, not because they share a source.

==(B) Causal linkage==: the UAPs themselves or their controllers are deploying electronic warfare against the observing aircraft. This is the more anomalous interpretation.

The collection does not contain enough data to discriminate decisively between A and B. The D58 case (the F-16 with noise jamming directly attributed to the objects on the same sensor display) is the strongest case for interpretation B. The D19 Shaddadi case is the cleanest case for interpretation A.

## Confidence

confidence:: moderate
basis:: Three independent incidents show the pattern. Sample size is small. Attribution is ambiguous.

## Implication

When evaluating future UAP observations, ==EMI and C2 link data should be a first-class element of the report== rather than a secondary note. The Range Fouler form already captures EA indications and noise jamming; the MISREP includes EMI sections. Cross-referencing these fields across incidents in any future Dataview pull is a high-priority follow-up.

## Related

- [[Incident - 2020-10 D58 Range Fouler]]
- [[Incident - 2020-09 Strait of Hormuz D62]]
- [[Incident - 2023-02-21 Shaddadi F-15E]]
- [[Sensor - APG-82 Radar]]
- [[Phenom - No Radar Return]]
