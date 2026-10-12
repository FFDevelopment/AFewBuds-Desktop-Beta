AFewBuds Desktop Beta 0.16.0-beta.16 — House Packing, Basement Grow Floor & Worker Animation Repair

VERIFIED SOURCE
- FFDevelopment/afewbuds-3d-prototype main @ de69bfed032fc2cc40efa0f6c416aac71fcf0bbb
- Full Godot, Windows/Linux exports and exported-world test passed: https://github.com/FFDevelopment/afewbuds-3d-prototype/actions/runs/38184273629

HOUSE PACKING BENCH
- Purchased Packing Bench III uses the full-size apartment-style finished bench rather than a smaller substitute, including its tabletop, trim tray, scale and jars.
- Real, independently stored house-bench inventory now supports the complete manual trimming and bagging interaction. Each scoop, pour and seal commits stock only after the completed interaction.
- Workers' trim and bag actions now target the actual purchased station and its scale/tray, with physical character props and animations. House and apartment inventory remain isolated.
- Bench III can fit against the usable packing-room wall at full size, with real wall, furniture and door collisions still enforced.

HOUSE ROOM / BASEMENT
- Packing, living and other upstairs placement boundaries follow the structural interior walls, not undersized legacy rectangles.
- Basement grow floor covers the usable east wing as well as the original grow section. Tents and equipment use basement-height coordinates, with stairwell and rail exclusion maintained.
- Furniture and bench interactions use their installed floor height; downstairs containers no longer float upstairs.
- Furniture placement and walk-around arrangement stay restricted to rooms and current floor; historical ownership/save keys remain unchanged.

PRODUCTION, SHOP & SAVES
- Retains independent production workers per apartment and house, per-property hiring, wages, automation, stock, duty, and transfer controls.
- Retains Level I equipment purchase flow, progression-gated station upgrades, tent LED upgrades, property deliveries, backpack tiers and Phone Shop upgrade browsing.
- Protects existing career, cash, genetics, property ownership, seeds, stock, account sessions and cloud saves.

RELEASE GATES
- Desktop passed 36 property staff checks, 37 shop checks, 44 room/basement checks, 33 packing parity checks, 106 property isolation checks, 85 equipment checks and the exported-world smoke test.
- Public Windows launcher, updater transactions, source pin, Windows/Linux export and SHA-256 assets must separately pass before publishing v0.16.0-beta.16.
