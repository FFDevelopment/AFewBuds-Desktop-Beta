AFewBuds Desktop Beta 0.16.0-beta.10

Source: FFDevelopment/afewbuds-3d-prototype @ 833761e9c4a38cbb3ab03779c2ec8bc3f481c665 (validated desktop development main). The unfinished Mission & Story Engine draft is NOT included.

- House workers navigate between rooms, doorways, stairway and stations instead of walking through walls; furniture rearrangement updates route blockers.
- Door staff use a distinct property role, walk at natural speeds, stand up before serving, pause to complete each sale and return using sofa-safe approach points.
- The current property manager keeps employees, grow tents, inventory, doors, bills and stock scoped to apartment or house.
- Add Low / Medium / High graphics quality presets in Pause > Settings, stored per device without changing career data or furniture models.
- Preserve the shared PropertyRegistry and ItemRegistry foundations for later expansions.
- Preserve beta.9 fixes for NPC visual identity and Reeves contacts after payoff.
- No player-character creator and no experimental mission/story draft in this release.

Upgrade safety: keep the existing user-data directory AFewBuds-Inventory-Preview, cloud account/session system and save schema; do not clear career data. The existing Windows launcher selects the latest verified v0.16.0-beta.N release. Direct older game executables and Linux ZIPs do not self-update.

Publication must pass the full Godot import, gameplay/career tests, Windows/Linux exports, exported-world smoke, launcher unit tests, launcher UI smoke and SHA-256 package checks.
