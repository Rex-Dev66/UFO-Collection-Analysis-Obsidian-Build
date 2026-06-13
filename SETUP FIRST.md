---
title: SETUP FIRST
tags: [setup, important]
type: reference
---

> [!IMPORTANT]
> If the live tables in this vault show as raw code instead of rendered tables, ==you need to install the Dataview community plugin.== This is a one-time setup.

## Install Dataview (required)

1. In Obsidian, open ==Settings== (gear icon, bottom left)
2. Go to ==Community plugins==
3. Click ==Turn on community plugins== if prompted (this is safe; it just enables the plugin marketplace)
4. Click ==Browse==
5. Search for ==Dataview==
6. Select the one by ==Michael Brenan==, click ==Install==
7. After install finishes, click ==Enable==

## Verify it works

Open `01 - Maps of Content/MOC - Incidents by Year.md`. You should see live tables of all incident notes. If you still see raw `TABLE ... FROM ...` code, the plugin is not yet enabled.

## Install Templater (recommended, optional)

The note templates in `10 - Conventions and Templates/` work as plain markdown templates without Templater. With the Templater plugin, you can auto-populate dates and prompt for fields at note creation.

1. Settings > Community plugins > Browse > search ==Templater== (by SilentVoid13)
2. Install + Enable
3. Settings > Templater > Template folder location > set to `10 - Conventions and Templates`
4. Optional: bind a hotkey to "Templater: Create new note from template"

## Enable Canvas (built-in)

Canvas is a core plugin (not community). Verify it is enabled:

1. Settings > Core plugins
2. ==Canvas== should be on

Open `2020 Arabian Gulf Cluster.canvas` in the vault root to see the spatial relationship view of the 2020 cluster (if it does not exist yet, it will be created in the next pass).

## Set graph view colors

1. Open the graph view (left sidebar icon or Ctrl+G)
2. Click the settings gear in the graph
3. Under ==Groups==, add:
   - Search `tag:#aor/centcom` > color: red
   - Search `tag:#aor/indopacom` > color: blue
   - Search `tag:#status/unresolved` > color: orange
   - Search `tag:#status/assessed-conventional` > color: green
   - Search `path:"02 - Incidents"` > color: yellow
   - Search `path:"03 - Sources"` > color: purple

The 2020 Arabian Gulf cluster will be visible as a tight community of orange-yellow nodes around the Arabian Gulf location node.

## Why some queries may show empty results

A Dataview query can be valid and still return nothing if:

- The incident notes are missing the field the query is filtering on
- The field name has a typo
- The link target in `WHERE contains(field, this.file.link)` is not actually present in any incident's frontmatter

If a query shows no results, open one or two incident notes and confirm they have the relevant frontmatter and inline fields populated.

## Once setup is done

Open [[Home]] for the main navigation. Read [[Vault Conventions]] before adding any new notes.
