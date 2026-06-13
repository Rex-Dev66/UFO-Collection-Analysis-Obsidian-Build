---
title: Vault Conventions
tags: [conventions, governance, reference]
type: reference
---

> [!IMPORTANT]
> This note is the single source of truth for how the vault is organized. If a convention is not written here, it is not a convention. Edit this note when you change anything structural.

## Note naming

Use plain title case with spaces. Avoid leading dates in filenames; put structured dates in frontmatter instead. Examples:

- ✅ `Incident - 2023-02-21 Shaddadi F-15E`
- ✅ `Source - DOW-UAP-D19 Syria February 2023`
- ❌ `2023-02-21_Shaddadi.md`

Note-type prefixes keep folders scannable: `Incident -`, `Source -`, `Location -`, `Platform -`, `Unit -`, `Sensor -`, `Witness -`, `Phenom -`, `Thesis -`, `MOC -`.

## Folder discipline

| Folder | Holds | Naming prefix |
| ------ | ----- | ------------- |
| `03 - Incidents` | One note per observation event | `Incident -` |
| `04 - Sources` | One note per source PDF | `Source -` |
| `05 - Locations` | Geographic entities | `Location -` |
| `06 - Platforms and Units` | Aircraft + units | `Platform -` or `Unit -` |
| `07 - Sensors and Equipment` | Sensors, radars, pods, weapons | `Sensor -` |
| `08 - Witnesses` | Named or categorical witnesses | `Witness -` |
| `09 - Phenomenology` | Observed signatures and behaviors | `Phenom -` |
| `10 - Patterns and Theses` | Cross-cutting hypotheses | `Thesis -` |

## Frontmatter standards

Every note has YAML frontmatter. Common keys:

| Key | Used by | Values |
| --- | ------- | ------ |
| `title` | All | Title as it appears in graph |
| `tags` | All | Lowercase, hyphenated, from controlled vocabulary |
| `type` | All | `incident`, `source`, `location`, `platform`, `unit`, `sensor`, `witness`, `phenom`, `thesis`, `moc`, `reference` |
| `status` | Incidents | `unresolved`, `probable-conventional`, `assessed-conventional`, `inconclusive` |
| `aor` | Incidents | `centcom`, `indopacom`, `eucom`, `africom`, `northcom`, `southcom`, `space`, `na` |
| `date_event` | Incidents | YYYY-MM-DD of event itself |
| `release_date` | Sources, Incidents | YYYY-MM-DD of declassification |
| `mdr_number` | Sources | e.g., `MDR 25-0094 thru 25-0099` |

## Controlled tag vocabulary

> [!WARNING]
> Do not invent ad-hoc tags. Add new tags to this list first, then use them. This is how the graph and Dataview stay useful.

### Agency

- `#agency/dow`
- `#agency/dod`
- `#agency/nasa`
- `#agency/fbi`
- `#agency/state`
- `#agency/cia`
- `#agency/ica` (Intelligence Community Assessment products)
- `#agency/army` (historical, pre-1947 unification and Dept of the Army)
- `#agency/navy` (historical service-origin documents)
- `#agency/usaf` (historical service-origin documents)
- `#agency/usg` (Congressional / White House / interagency correspondence)
- `#agency/aaro` (AARO-authored analysis products)

### Area of responsibility

- `#aor/centcom`
- `#aor/indopacom`
- `#aor/eucom`
- `#aor/africom`
- `#aor/northcom`
- `#aor/southcom`
- `#aor/space`
- `#aor/na` (no specific AOR; domestic, oceanic, or undisclosed)

### Platform

- `#platform/f-15e`
- `#platform/f-a-18`
- `#platform/f-16`
- `#platform/p-8a`
- `#platform/mh-60r`
- `#platform/apollo-csm`
- `#platform/apollo-lm`
- `#platform/skylab`
- `#platform/civilian-aviation`
- `#platform/ground-observer`
- `#platform/mq-9`
- `#platform/rq-4`
- `#platform/p-3`
- `#platform/ec-130`

### Phenomenology

- `#phenom/round`
- `#phenom/linear`
- `#phenom/spherical`
- `#phenom/white-hot`
- `#phenom/dark-sphere`
- `#phenom/silent`
- `#phenom/no-exhaust`
- `#phenom/no-radar-return`
- `#phenom/no-iff`
- `#phenom/orb`
- `#phenom/red-orb`
- `#phenom/mother-orb` (orb apparently launching/expelling smaller orbs)
- `#phenom/plasma` (plasma/luminous-core sphere)
- `#phenom/disc`
- `#phenom/translucent`
- `#phenom/kite` (kite/diamond-shaped object)
- `#phenom/shape-shifting` (object reported to morph or "cloak")
- `#phenom/metallic` (metallic/opaque surface reported)
- `#phenom/reflective` (specular/reflective surface reported)
- `#phenom/cold-ir` (cold/dark IR signature against background)
- `#phenom/high-altitude` (sustained very-high-altitude observation)

### Sensor

- `#sensor/eoir`
- `#sensor/atflir`
- `#sensor/sniper-se`
- `#sensor/radar-apg82`
- `#sensor/visual-only`
- `#sensor/night-vision` (night-vision device / thermal binoculars)
- `#sensor/photographic` (handheld camera / phone stills)

### Status

- `#status/unresolved`
- `#status/probable-conventional`
- `#status/assessed-conventional`
- `#status/inconclusive`
- `#status/keyword-false-positive`

### Source type

- `#source/misrep`
- `#source/range-fouler`
- `#source/email-correspondence`
- `#source/fd-302`
- `#source/diplomatic-cable`
- `#source/transcript`
- `#source/debrief`
- `#source/sensor-image`
- `#source/historical`
- `#source/fd-1057` (FBI internal electronic communication)
- `#source/intel-assessment` (ICA / analytic assessment)
- `#source/intelligence-report` (CIA IIR / field intelligence report)
- `#source/digital-rendering` (AI/artist reconstruction of a sighting)
- `#source/notional-map` (illustrative geospatial reconstruction)
- `#source/correspondence` (letters / Congressional / White House)
- `#source/study` (service or agency analytic study)
- `#source/sensor-video` (declassified sensor full-motion video)
- `#source/sketch` (forensic / composite witness sketch)

### Workflow

- `#needs-content-extraction` (note exists but the source document has not yet been fully extracted; SKELETON stage)

### Release process

- `#release/aaro`
- `#release/mdr`
- `#release/state-dept`
- `#release/foia`
- `#release/pursue` (Presidential Unsealing and Reporting System for UAP Encounters; WAR.GOV/UFO rolling tranches)

## Linking discipline

Every incident note links to: its location, its platform, its unit, its sensor(s), any witness(es), its source document(s), and any pattern(s) it supports or refutes.

Use `[[wikilinks]]` exclusively. Use display text only when the link target name does not read naturally in the sentence: `[[Location - Muwaffaq Salti Air Base|OJMS]]`.

When an entity has multiple common names, set aliases in its frontmatter:

```yaml
aliases: [OJMS, Muwaffaq Salti, Azraq]
```

## Dataview conventions

When you write an inline Dataview field for an incident, use these key names so the queries in the MOCs work:

```
date_event:: 2023-02-21
time_z:: 0025
aor:: centcom
country:: Syria
location:: [[Location