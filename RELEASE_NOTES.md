AFewBuds Desktop Beta 0.16.0-beta.13 — Correct Packing Benches, Curbside Delivery, Backpack Upgrades

Exact isolated source: FFDevelopment/afewbuds-3d-prototype @ f7b6a5529b4a77a6217ce0eff1f1e8ef8122c410
Source branch: hotfix/testers-shop-bench-delivery-backpack-20261011. Experimental custom-character art and Mission & Story draft are EXCLUDED.

RESTORED
- Market-purchased Packing Benches now reuse the approved apartment model with its detailed scale, trim tray, tools, bag supply and jars. The placement preview uses the same finished model, not the simplified temporary box-table.
- Existing hand-trimming (scissors) and drag-to-bag/weigh/seal interactions remain connected to the packing station and its property-scoped inventory.
- Central Market cart checkout now offers Market Pickup, Apartment Curbside Delivery or House Curbside Delivery for equipment/furniture, limited to properties actually controlled by the player. The destination is checked before charging; paid delivery crates remain at the chosen curb until collected.
- Seeds and fertilizer still use Central Market pickup (or automatic collection while standing at checkout), never automatic house stock transfer.
- Backpack level upgrade buttons restored at Central Market > Upgrades: 35/55/80/110 lb, upgrade costs $250/$750/$1,750; saved backpack level retained and each purchase charges once.
- Phone > Shop > Shop Upgrades now shows backpack level, next tier, prices and equipment families. Phone catalog is read-only; upgrades are bought onsite.

UNCHANGED
- Prior beta.12 house furniture arrangement fix stays intact.
- No edits to production-worker AI or grow-tent planting cadence.
- Existing accounts, careers, money, furniture positions, tents, stocked packing benches, property inventory, workers, story and saved backpack level are preserved.
- Save path remains AFewBuds-Inventory-Preview; cloud/account sync and the original automatic SHA-256 Windows Launcher update/rollback mechanism are unchanged.

Release gating: full desktop Godot import, real house curb/delivery and packing bench tests, careers/save suites, Windows/Linux exports and smoke tests, updater/launcher tests, SHA-256 packaging. Windows users opening the existing AFewBuds Launcher should receive beta.13 when publication succeeds; direct executable and Linux ZIP users update manually.
