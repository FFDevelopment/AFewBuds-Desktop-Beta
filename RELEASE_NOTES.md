AFewBuds Desktop Beta 0.16.0-beta.15 — Full House Boundary Fix

Verified development source: FFDevelopment/afewbuds-3d-prototype main @ ce0fabdffb6e5dd8a0b86737d4a8283782b1e4c3
Validated desktop source + Windows/Linux exports: https://github.com/FFDevelopment/afewbuds-3d-prototype/actions/runs/38180093492
Matching mobile source + physical room checks: https://github.com/FFDevelopment/afewbuds-cloud-test/actions/runs/38180132122

HOUSE ROOM / FURNITURE FIXES
- All six upstairs house rooms (living, packing, kitchen, bathroom, bedroom and grow) use furniture placement bounds aligned to the interior structural wall faces, rather than legacy rectangles leaving 25–45 cm gaps.
- Packing Bench III uses its approved detailed model and can be placed flush with clear solid walls to within a narrow millimetre margin. Actual walls, furniture, doors, window coverings and fixtures still block physically invalid placements.
- Basement grow-room bounds expand to usable floor near side and front walls while preserving the staircase/railing corridor. Grow equipment remains floor-aware and cannot be placed in walls, stairs, or upstairs space by accident.
- Historical registry boundaries used for property IDs and ownership are preserved; only safe furniture placement bounds were refined.
- Walk-around arrangement and placement validation use the same house room geometry. New items and pre-existing saved careers are supported.

PREVIOUS TESTER SYSTEMS PRESERVED
- One production worker per owned property, with separate hiring from Contacts, transfers, duty, autoscheduling, tasks, wages and finite-stock offline care.
- Starter Level I market equipment with in-place paid upgrades, Grower-level unlock requirements, and individual tent LED lighting upgrades.
- Finished apartment-style packing benches, working trim/bag mechanics, property delivery drop-offs, backpack capacity upgrades and Phone Shop upgrade browsing.
- Existing accounts, money, seed/plant genetics, placed furniture, property ownership and all inventory/save/sync data are retained.

RELEASE VALIDATION
- Complete desktop Godot regression and Windows/Linux export tests passed, including new physical house/basement boundary coverage.
- Full launcher regression, Windows build, game export smoke, and SHA-256 release asset integrity must pass before a desktop beta tag is published.
