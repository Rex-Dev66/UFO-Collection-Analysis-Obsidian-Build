---
title: Thesis - Keyword Sweep False Positives
tags: [thesis]
type: thesis
status: provisionally-supported
confidence: high
---

## Hypothesis

AARO-era declassification releases include a non-trivial fraction of documents tagged "UAP" or "UFO" that are not substantively about UAPs. These false positives arise from keyword-driven discovery against legacy document corpora.

## Reasoning

1. The [[Source - 2001 Moscow Cable UFOs Over Georgia|2001 Moscow cable]] is a clear example: a diplomatic cable about Russian airspace violations, where "UFO" appears only as sarcastic Russian diplomatic euphemism. The U.S. Ambassador's drafting comment explicitly notes the absurdity of treating it as a UAP report.
2. Other historical archival documents in the collection (e.g., German Armament Equipment Documents 1944-1945) likely arrived in the UAP release pipeline through keyword matches that surface incidental rather than substantive content.

## Supporting documents

- [[Source - 2001 Moscow Cable UFOs Over Georgia]]

## Disconfirming evidence

- Most documents in the collection ARE substantively about UAPs. The false-positive rate is non-zero but is not the dominant pattern.

## Confidence

confidence:: high (the pattern is documented for at least one source)
basis:: At least one clear example exists; reasoning chain about keyword-driven discovery is structural.

## Implication

- [ ] Tag any future documents that turn out to be false positives with `#status/keyword-false-positive`
- [ ] When counting "UAP report" totals from AARO releases, deduct documents that fail substantive review
- [ ] Note the false-positive rate as a metric in its own right for the AARO release process
