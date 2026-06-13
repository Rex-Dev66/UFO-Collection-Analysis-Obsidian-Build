# UFO / UAP Collection Analysis — Obsidian Vault

An [Obsidian](https://obsidian.md) knowledge vault that structures, cross-references, and analyzes a collection of **publicly released and declassified U.S. government documents** on Unidentified Anomalous Phenomena (UAP / "UFOs").

It turns a pile of source PDFs — DoD/DOW mission reports, State Department cables, CIA cables, FBI case files, NASA debriefings, and historical service studies — into a navigable network of incidents, sources, locations, platforms, sensors, witnesses, observed phenomenology, and cross-cutting analytical theses.

> [!NOTE]
> **What this is and isn't.** This is a *research and organization* project built on publicly available, officially released material. Cataloging a reported event or reproducing a document's original classification marking (e.g. "SECRET//NOFORN") is a statement about the **source record**, not a claim that any phenomenon is extraterrestrial or that any conclusion is established fact. Analytical hypotheses live in `09 - Patterns and Theses` and are explicitly labeled as hypotheses. Treat everything here as structured notes for study, not as settled truth.

---

## Contents at a glance

| Note type | Count | Folder |
| --------- | ----: | ------ |
| Incidents (observation events) | 53 | `02 - Incidents` |
| Sources (one per source document) | 82 | `03 - Sources` |
| Locations (places, AORs, regions) | 29 | `04 - Locations` |
| Platforms & Units (aircraft, military units) | 20 | `05 - Platforms and Units` |
| Sensors & Equipment (pods, radars, weapons) | 6 | `06 - Sensors and Equipment` |
| Witnesses (named or categorical) | 10 | `07 - Witnesses` |
| Phenomenology (shapes, behaviors, signatures) | 10 | `08 - Phenomenology` |
| Patterns & Theses (analytical hypotheses) | 11 | `09 - Patterns and Theses` |
| Canvases (spatial / relationship maps) | 14 | `09 - Patterns and Theses/Canvas` |
| Maps of Content (Dataview navigation pages) | 5 | `10 - MOCs` |
| Reference (glossary, timeline, release authorities) | 7 | `99 - Reference` |

~247 interconnected Markdown notes in total.

---

## Folder structure

| Folder | Purpose |
| ------ | ------- |
| `00 - Inbox` | Drop-in zone for unprocessed notes |
| `01 - Conventions and Templates` | Vault rules, controlled vocabulary, and note templates |
| `02 - Incidents` | One note per UAP observation event |
| `03 - Sources` | One note per source document (PDF/image/cable) |
| `04 - Locations` | Geographic entities — places, AORs, MGRS regions |
| `05 - Platforms and Units` | Aircraft types and military units |
| `06 - Sensors and Equipment` | EO/IR pods, radars, weapons systems |
| `07 - Witnesses` | Named witnesses or witness categories |
| `08 - Phenomenology` | Observed behaviors, shapes, and signatures |
| `09 - Patterns and Theses` | Cross-cutting analytical hypotheses + Canvas maps |
| `10 - MOCs` | Navigation pages built from live Dataview queries |
| `99 - Reference` | Acronyms, glossary, timeline, release authorities |

---

## Getting started

### 1. Open the vault in Obsidian
Clone or download this repository, then in Obsidian choose **Open folder as vault** and point it at the repository root.

```bash
git clone https://github.com/Rex-Dev66/UFO-Collection-Analysis-Obsidian-Build.git
```

### 2. Install the Dataview plugin (required for live tables)
Many navigation pages (`Home`, the MOCs) use live [Dataview](https://github.com/blacksmithgu/obsidian-dataview) queries. Without the plugin you'll see raw `TABLE ... FROM ...` code instead of rendered tables.

1. **Settings → Community plugins → Turn on community plugins**
2. **Browse → search "Dataview"** (by Michael Brenan) → **Install → Enable**

### 3. (Optional) Templater + Canvas
- **Templater** (by SilentVoid13) auto-populates dates and prompts for fields when creating notes from the templates in `01 - Conventions and Templates`. The templates also work as plain Markdown without it.
- **Canvas** is a built-in core plugin — verify it's enabled to view the `.canvas` relationship maps in `09 - Patterns and Theses/Canvas`.

A full walkthrough — including suggested graph-view color groups — is in [`SETUP FIRST.md`](SETUP%20FIRST.md).

### 4. Start navigating
Open [`Home.md`](Home.md) for the main hub, then explore the Maps of Content:

- **MOC - Incidents by Year** — chronological index
- **MOC - Incidents by Location** — geographic index
- **MOC - Platforms and Units** — by aircraft / unit
- **MOC - Sources** — by source document
- **MOC - Patterns and Theses** — analytical hypotheses

---

## How the vault is organized

The single source of truth for structure is [`01 - Conventions and Templates/Vault Conventions.md`](01%20-%20Conventions%20and%20Templates/Vault%20Conventions.md). Highlights:

### Naming
Plain title case with a note-type prefix; structured dates go in frontmatter, not filenames.
- ✅ `Incident - 2023-02-21 Shaddadi F-15E`
- ✅ `Source - DOW-UAP-D19 Syria February 2023`

### Frontmatter
Every note carries YAML frontmatter. Common keys include `type` and `tags`, and — for incidents — `status`, `aor`, `date_event`, and `release_date`; sources add `mdr_number`. These fields power the Dataview tables. (Note creation/modification dates are handled automatically by Obsidian, so they aren't duplicated in frontmatter.)

### Incident status taxonomy
`unresolved` · `probable-conventional` · `assessed-conventional` · `inconclusive`

### Controlled tag vocabulary
Tags are namespaced and drawn from a fixed list (no ad-hoc tags):
- **Agency** — `#agency/dow`, `#agency/dod`, `#agency/cia`, `#agency/fbi`, `#agency/nasa`, `#agency/state`, `#agency/aaro`, …
- **AOR** — `#aor/centcom`, `#aor/indopacom`, `#aor/eucom`, `#aor/northcom`, …
- **Platform** — `#platform/f-15e`, `#platform/f-a-18`, `#platform/p-8a`, `#platform/apollo-csm`, …
- **Phenomenology** — `#phenom/orb`, `#phenom/white-hot`, `#phenom/disc`, `#phenom/no-radar-return`, …

### Templates
`01 - Conventions and Templates` contains a template for every note type (Incident, Source, Location, Platform, Unit, Sensor, Witness, Thesis) so new entries stay consistent.

---

## About the source material

Source documents come from the rolling **PURSUE / WAR.GOV/UFO** public-release program (Releases 01–03, May–June 2026) and earlier declassification tranches, routed through the All-Domain Anomaly Resolution Office (**AARO**). The collection spans:

- **DOW / DoD** mission reports, range-fouler debriefs, and correspondence
- **State Department** diplomatic cables
- **CIA** UFO-series cables and the 1953 Robertson Panel material
- **FBI** domestic case files and witness interviews
- **NASA** Gemini/Apollo crew debriefings and visual materials
- **Historical service studies** (Army/Navy/USAF, 1948–1953)

Geographically the corpus is CENTCOM-heavy (~70%), with INDOPACOM, EUCOM/Mediterranean, and a historical/domestic remainder. See [`01 - Conventions and Templates/Collection Overview.md`](01%20-%20Conventions%20and%20Templates/Collection%20Overview.md) and `99 - Reference/Release Authorities` for full provenance.

### Tracing a note back to its source

The raw source PDFs and images are **not** included in this repository — it holds the analytical layer (structured notes and cross-references) built on top of them. Instead, **every source note cites its original released document by filename** in a `source_document::` field, for example:

```
source_document:: `DOW-UAP-D12-Mission-Report-Iraq-May-2022.pdf`
```

That filename is the document's name as released by the originating agency, so you can identify the exact record a note is based on and locate it from the original public release (AARO / agency FOIA reading rooms / the PURSUE program). The image-index notes list their renderings the same way. These are provenance citations, not downloadable links — the documents themselves are obtained from the original release, not from this repo.

---

## Contributing / extending

If you fork this to add your own notes:

1. Read `Vault Conventions.md` first.
2. Use the matching template from `01 - Conventions and Templates`.
3. Reuse existing tags from the controlled vocabulary — add new ones to the conventions note *before* using them, so the graph and Dataview queries stay coherent.
4. Keep one event per incident note and one document per source note.

---

## License

The notes and analysis in this repository are released under the **Creative Commons CC0 1.0 Universal** public-domain dedication — see [`LICENSE`](LICENSE). You are free to copy, modify, and reuse this material for any purpose, without permission or attribution.

Underlying source documents are works of the U.S. government and were released to the public by the originating agencies; their status is governed by those releases, not by this repository's license.
