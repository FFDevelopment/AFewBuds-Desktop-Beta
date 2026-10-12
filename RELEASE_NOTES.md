AFewBuds Desktop Beta 0.16.0-beta.19 — Physical Customer Visits, Emergency Heat Shutdown & Storage/UI Fixes

VERIFIED DESKTOP SOURCE
- FFDevelopment/afewbuds-3d-prototype main @ 48871a0671119ffdca7a66bab8036643cb3aecad
- Full headless Godot gameplay, mission and physical visitor, inventory, staff, save, Windows/Linux export and exported-world validation:
  https://github.com/FFDevelopment/afewbuds-3d-prototype/actions/runs/38299690391

CUSTOMER INTERACTION
- First playable physical doorstep customer experience at the apartment. Open the actual door and interact with the visible 3D NPC using the existing SELL, SUBSTITUTE or DECLINE actions.
- Clients walk down the sidewalk before despawning away from the front door. Some buyers can ask to hang out after a purchase; a completed social encounter gives relationship loyalty once per customer per in-game day.
- Special encounters such as Agent Reeves retain their existing story route. The legacy peephole remains as a fallback. Roaming pedestrians and off-site scheduled meetups are still in development.

HIGH HEAT / OWNER CONTROL
- Phone > Heat and the owned property menu offer CLOSE SHOP and SHUT DOWN & LAY LOW without any on-duty worker or Heat prerequisite.
- Off-duty workers still accept emergency CLOSE and SHUT DOWN commands, while OPEN, REOPEN and return-to-duty remain restricted at high Heat or during raids.
- Lay Low closes incoming business and saves/restores the property's equipment settings without reassigning workers or mixing property state.

INVENTORY & LISTING
- Property stock listings include all installed storage units at that property. Secondary storage no longer appears missing.
- Reservations are subtracted exactly once. Player, dealer, production and staff sales/deposits debit and credit the correct physical storage bins without duplication.
- LIST/UNLIST actions remain readable on compact desktop/window and mobile-style layouts.

TESTED / SAFETY
- Each platform has separate independent tests for all combined features. The source regression completed successfully.
- Public workflow must separately validate Windows updater, launcher smoke, save safety, Windows/Linux exports, checksum packaging and verified release artifacts.
- Same account and career protocol, Godot save directory (AFewBuds-Inventory-Preview), legacy storage assets, house/apartment ownership, genetics, cash and employee assignments as the last public release.
