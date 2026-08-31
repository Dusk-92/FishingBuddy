# FishingBuddy code provenance

Audit date: 2026-08-31

## Historical addon identity

The current package retains the historical Fishing Buddy 0.8.8e metadata and
documentation associated with Sutorix.

The old `readme.txt` and `changes.txt` are retained as important provenance
records and should not be replaced solely by the modern README.

## GitHub ancestry

GitHub metadata confirms:

`aim2kill/FishingBuddy`
→ `refaim/FishingBuddy`
→ `Dusk-92/FishingBuddy`

Immediate upstream baseline used for comparison:

`4671cbd714265c6c19d81558dc33d0ba339fa43f`

Pre-audit Dusk-92 head:

`f8daade4cf6b70f4c65587c7b1636f658ccdbc06`

The Dusk-92 fork was five commits ahead of that immediate upstream baseline.

## Dusk-92-specific runtime changes

The compare result shows only one runtime file changed by the Dusk-92 commits
after the immediate upstream baseline:

- `FishingBuddy.lua`

Git history records the relevant changes as:

- `7cda85a8642fc729454eac8ef6afe9d6c1ec02b1`
  - "add Driftwood Fishing Pole"
- `988fa5bf60eb5dfdb80c520d74283d8dcf8e2df7`
  - "Add fish pole and Lure from the survival profession"
- `ae4b2634c463d31e630610fe11c73b097d5de2ba`
  - "Update addon name from FishingBuddy to OctoWow"

The other Dusk-92 commits in that comparison update the README.

## Historical third-party provenance

The source contains explicit historical attribution:

- `FishingExtravaganza.lua`:
  "Map support liberally borrowed from GuildMap, by Bru on Blackhand"
- `readme.txt` credits TackleBox, Impp's Fishing DB, QuickWeaponSwap, and
  GuildMap.

These statements are retained as the most authoritative surviving provenance
evidence for those historical relationships.

## Current official rights status

The current official Fishing Buddy and Fishing Buddy (Classic) projects on
CurseForge are marked "All Rights Reserved".

Neither `aim2kill/FishingBuddy` nor `refaim/FishingBuddy` contains a
standalone project-wide LICENSE file.

For that reason, this fork does not infer a permissive license merely from the
existence of public historical source code or a public GitHub fork network.

## Maintenance rule

Future changes should continue to distinguish:

1. inherited Fishing Buddy code;
2. historically attributed third-party-derived/reference material;
3. Dusk-92-authored modifications;
4. external optional compatibility targets.

Do not replace that distinction with a blanket license claim.
