# FishingBuddy third-party notices

Audit date: 2026-08-31

This file records known upstream sources, historical credits, optional
dependencies, asset provenance, and current licensing signals for the Dusk-92
FishingBuddy fork.

Existing source comments, `readme.txt`, `changes.txt`, Git history, and
upstream repository metadata remain part of the provenance trail.

## Historical Fishing Buddy

The addon metadata identifies:

- Title: Fishing Buddy
- Version: 0.8.8e
- Author/contact identity: Sutorix

The historical `readme.txt` describes Fishing Buddy as combining ideas and
functionality from multiple earlier fishing-related addons and credits:

- TackleBox
- Impp's Fishing Info / Fishing DB
- QuickWeaponSwap
- GuildMap
- many other community addons

The historical source also contains more specific attribution. For example,
`FishingExtravaganza.lua` states that its map support was "liberally borrowed
from GuildMap, by Bru on Blackhand".

These historical credits are preserved as provenance evidence. This repository
does not erase them or convert them into claims of original authorship.

## Current official upstream licensing signal

The current official Fishing Buddy projects maintained by Sutorix on CurseForge
are marked:

- **All Rights Reserved**

References:

- https://www.curseforge.com/wow/addons/fishingbuddy
- https://www.curseforge.com/wow/addons/fishing-buddy-classic

No standalone LICENSE file was present in either known GitHub ancestor checked
during this audit:

- `aim2kill/FishingBuddy`
- `refaim/FishingBuddy`

Accordingly, this fork does **not** claim that inherited Fishing Buddy code is
MIT, GPL, public domain, or otherwise freely relicensed.

The repository root `LICENSE` is intentionally a mixed-origin rights notice,
not a permissive license for inherited code.

## GitHub fork chain

GitHub repository metadata confirms this ancestry:

1. `aim2kill/FishingBuddy`
   - https://github.com/aim2kill/FishingBuddy
2. `refaim/FishingBuddy`
   - https://github.com/refaim/FishingBuddy
3. `Dusk-92/FishingBuddy`
   - https://github.com/Dusk-92/FishingBuddy

The immediate upstream commit used as the baseline for this fork was:

- `4671cbd714265c6c19d81558dc33d0ba339fa43f`
- "Merge ilithyia-addons fork (v0.8.8e)"

## Dusk-92 changes

Comparing the immediate upstream baseline above with the pre-audit Dusk-92 head
`f8daade4cf6b70f4c65587c7b1636f658ccdbc06` shows changes only to:

- `FishingBuddy.lua`
- `README.md`

The runtime changes documented in Git history add OctoWoW-oriented fishing pole
and lure entries, including the Driftwood Fishing Pole and survival-profession
items.

The README was rewritten to explain the addon and the OctoWoW-maintained fork.

All other inherited runtime files and assets were unchanged relative to the
immediate upstream baseline at the start of this documentation pass.

## Optional external addon integrations

`FishingBuddy.toc` lists optional compatibility with external addons such as:

- OutfitDisplayFrame
- Outfitter
- myAddOns
- FuBar
- Titan
- InfoBar
- Gatherer
- ButtonHole

These projects are not made part of FishingBuddy merely because compatibility
code or optional dependency declarations exist.

Compatibility does not imply affiliation, endorsement, or a common license.

## Historical third-party-derived/reference material

Some source modules contain historical references to other addon projects.

In particular:

- `FishingExtravaganza.lua` credits map support borrowed from GuildMap by Bru
  on Blackhand.
- The historical README credits TackleBox, Impp's Fishing DB,
  QuickWeaponSwap, and GuildMap.
- The changelog records integration work involving Gatherer, Outfitter, Titan,
  InfoBar, Cosmos-team discoveries, and other addon ecosystems.

This audit did not independently establish a complete license chain for every
historical referenced or adapted component.

Those references are therefore preserved rather than guessed or silently
relicensed.

## Visual assets

The complete `Icons/` directory in this fork is byte-identical at Git tree
level to the immediate upstream `refaim/FishingBuddy` directory.

See `Docs/ASSET_PROVENANCE.md`.

## Project identity and trademarks

Canonical maintained fork:

- https://github.com/Dusk-92/FishingBuddy

World of Warcraft, Warcraft, Blizzard Entertainment, and associated names,
marks, artwork, and game assets remain the property of their respective rights
holders.

See `PROJECT_IDENTITY.md`.

## Preservation rule

Do not remove historical source comments, author/contact metadata, upstream
links, changelog attribution, or third-party credits merely because code is
later modified.

When replacing or substantially rewriting inherited material, update the
provenance record rather than erasing the historical chain.
