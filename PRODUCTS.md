# Game Developer Toolchain

All 18 products in this package.

Every entry below is taken from the package's product inventory. Nothing here is a plan or a
roadmap item; all of it is built.

---

## Deck Forge

22 files, 193 tests

Roguelike deckbuilder engine with a balance simulator that plays the game thousands of times and reports which cards are broken.

## Access Layer

22 files, 178 tests

Accessibility and input remapping: full key and pad rebinding with three slots per action, plus the rest of what console submission checklists require.

## Localization Bus

20 files, 197 tests

Finds text already buried in a codebase, centralises it, and lets a game ship in more than one language. No string tagging required first.

## Crossplay Bus

22 files, 133 tests

Cross-platform lobbies, matchmaking and one player identity across every device.

## The Autonomous Roblox Plugin Factory

13 files, 75 tests

Reads developer forums for recurring complaints, turns them into feature requests, generates finished plugins with thumbnails and docs, and drafts the store listing.

## Anime RPG Kit

16 files, 63 tests

Turn-based battle middleware: turn and timing engine, skill trees, party and formation handling, status effects, damage formulas.

## Living World Middleware

23 files, release gate passes

Drops a fifty-system living world into an existing game through a detect, plan and apply sequence, with adapters for Godot, Roblox and Unity.

## Idle Engine

10 files, 72 tests

Idle and incremental game core: offline earnings maths, prestige loops, large-number handling, balance curves.

## Cozy Kit

13 files, 68 tests

Life-simulation substrate: farming, crafting, relationships, calendar, daily character schedules, day and night cycle.

## Economy Balancer

11 files, 57 tests

Simulates currency sinks and sources, detects inflation, and tunes drop rates.

## Instant Play Wrapper

10 files, 31 tests

Turns a web build into a fast-loading browser demo that asks for a wishlist at the right moment. Static files only.

## Loot Odds Desk

9 files, 37 tests

Disclosure and compliance layer for crates, gacha and randomised bundles. Turns a legal exposure into a generated disclosure document.

## Release Bus

11 files, 20 tests

One command builds, packages, writes the changelog and prepares a store release. Never asks for store credentials.

## Remote Config Bus

6 files, 62 tests

Live settings and a kill switch for shipped games, with the studio bringing its own backend rather than being locked to a vendor.

## Studio Black Box

1 file, 11 tests

Offline flight recorder for playtests: session recording, one-button bug reports, local funnels and heatmaps, crash grouping. Nothing leaves the machine.

## NPC Guardrail

1 file, 13 tests

Safety layer for AI characters. Blocks jailbreak attempts before they reach the studio's model, checks replies for out-of-character lines, and serves a fallback when the model is slow.

## Progress Vault

1 file, 12 tests

Save system: version-stamped saves, automatic forward migration across patches, signing so an edited save can be told from a genuine one.

## Mod Bus

1 file, 12 tests

Safe mod loading: manifest validation, dependency-ordered loading, and per-mod isolation so one broken mod does not take the game down.

---

Full detail, including file-level inventory and provenance, is in the data room, available under a
signed non-disclosure agreement. See [ACQUISITION.md](ACQUISITION.md).
