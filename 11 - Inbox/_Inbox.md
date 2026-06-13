---
title: _Inbox
tags: [inbox]
type: reference
---

> [!NOTE]
> Drop unprocessed notes here. When you have time, file them into their proper folder, populate the frontmatter, and add the wiki-links.

## Vault status

==All declassified case documents are represented and the DOW UAP D-series is fully extracted.== Current state:

- 53 incident notes, all populated from their source documents (no empty stubs)
- 82 source notes (one per source document; large historical archives are index-tracked, see below)
- Full entity coverage: 29 locations, 20 platforms/units, 6 sensors, 10 witnesses, 10 phenomenology notes
- 11 thesis notes and 14 Canvases in `10 - Patterns and Theses`
- 5 MOC notes with Dataview queries
- Reference: acronyms, timeline, release authorities, AARO overview, Operation Inherent Resolve, Russian KCTG, SPEAR

## Remaining work (genuinely open)

These are large historical archives that are deliberately index-tracked rather than parsed line-by-line. They are catalogued in [[Historical Archive Index]] and [[_Unread Sources Index]].

- [ ] Read the 1949 Flying Discs Army file (`342_..._319.1-Flying-Discs-1949.pdf`), the canonical early-era anchor.
- [ ] Read the Project Sign / Grudge Incident Summaries (`38_143685_box7` series, 1-233).
- [ ] Read the FBI main UFO file 62-HQ-83894 (10 sections + serials).
- [ ] Read the oversized NASA debriefs (Apollo 11 D4, Apollo 17 D5/D6, Skylab D7) and the Gemini debriefings.
- [ ] Follow up on the 1994 Tajik Air photographs (see [[Witness - Captain Ed Rhodes and Tajik Air Crew]]), the highest-value single lead in the collection.

## Media not included in this repository

The source Collection folder also holds 28 `DOD_111XXXXXX.mp4` sensor videos and 32 FBI-labelled sensor stills. These binary media files are catalogued in [[DOD Video Catalog]] and [[FBI Photo Series Index]] but are not committed to the vault repository.

## Process notes

- Every incident links to its location, platform, unit, sensor(s), witness(es), source(s), and any pattern it supports. Use [[Template - Incident]] when adding a new one.
- Dataview queries depend on consistent inline fields (`location::`, `platform::`, `status::`, etc.). Copy the field set from [[Template - Incident]].
- Status tags evolve: `inconclusive` once read but underdetermined -> `unresolved` or `assessed-conventional` once analyzed. The `needs-content-extraction` tag is reserved for documents not yet parsed.
