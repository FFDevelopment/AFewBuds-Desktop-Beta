AFewBuds Desktop Beta 0.16.0-beta.18 — Combined Stock Across Multiple Storage Units

VERIFIED DESKTOP SOURCE
- FFDevelopment/afewbuds-3d-prototype main @ 4105509fa94e18a9f5b6517dd8d547dd7db7d0f0
- Full Godot source build, isolated-save tests, Windows/Linux exports and exported world validated:
  https://github.com/FFDevelopment/afewbuds-3d-prototype/actions/runs/38294860457
- All 28 new multi-storage checks passed alongside existing 55 production worker checks and the rest of the gameplay suite.

PROPERTY INVENTORY
- Listing menu, Storage window and Property overview count packaged product in every installed storage unit at that property, not only the legacy primary shelf.
- Reservations apply once across a property's physical inventory. Selling first consumes available packaged grams across that property's installed units without negative stock, double sales, or consuming reserved grams.
- Stock in a secondary shelf can be listed even when the original primary shelf is empty.
- Manual packaging, production workers, and Dealer Locker returns distribute deposits across available unit capacity instead of overfilling primary storage.
- Dealer and staffed doorstep sales as well as friend purchases debit actual storage records. Uninstalled or packed storage units are excluded from available stock.
- House and apartment balances, metadata, pricing, reservations and ownership remain independent.

SAFETY
- Storage record IDs and each original inventory payload are preserved; no save migration, character reset, deletion, or destructive aggregation is performed.
- Existing cloud and local saves, properties, workers, furniture upgrades, career stats, and updater stay unchanged.
- Public release re-verifies launcher and update transactions, complete gameplay suite, Windows/Linux exports, and SHA-256 packages before publication.
