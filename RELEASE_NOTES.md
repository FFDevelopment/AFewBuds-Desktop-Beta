AFewBuds Desktop Beta 0.16.0-beta.14 — Independent Property Workers and Equipment Progression

Verified development source: FFDevelopment/afewbuds-3d-prototype @ 780f4436bcda670e0bbbe55d7d7d285ca8b0fb3f
Validated desktop CI: https://github.com/FFDevelopment/afewbuds-3d-prototype/actions/runs/38172205573

PRODUCTION WORKERS
- One independent production worker position at each controlled property: apartment and house. Hire a generic worker from that property's management screen or offer a loyal friend production work for a specific property through Contacts.
- Each worker has its own assignment, duty status, navigation actor, tasks, auto-plant preference, wage and save record. Work uses only that property's stored seeds, harvests and equipment.
- Transferring a worker frees the source position, does not duplicate a character, and is blocked when the destination position is occupied. Firing one worker does not terminate the other.
- Existing workers and their property assignments migrate into the new per-property records. Active workers may continue limited finite-stock watering/fertilizing while away, without offline planting, harvesting, processing or sales.

EQUIPMENT & FURNITURE
- Central Market sells the Level I version of equipment. Upgrade each placed bench, shelf, storage or dealer locker from Furniture Arrangement for the tier price difference, subject to the original Grower-level requirements.
- Grow tents retain their separate 1/2/3/4-plant sizes and include Basic Light I. Upgrade a specific tent to LED Grow Light II for $320 at the required level, replacing the fixture without uprooting planted crops.
- Tight centimeter furniture placement and room-edge fit let Packing Bench III sit near a wall without rejecting harmless baseboards; actual structural walls, doorways and furniture intersections remain blocked.

RETAINED FROM PREVIOUS TESTER HOTFIX
- Approved apartment-style packing benches and trim/bag animations for purchased stations, property curbside equipment deliveries, backpack upgrades, and the read-only Phone Shop upgrade catalog remain included.
- Existing accounts, property ownership, inventory, placed furniture, financial records, cloud/account sync, and the AFewBuds-Inventory-Preview save directory are preserved.

RELEASE GATES
- Full Godot regression suite passed: independent property workers (29), tester shop (37), property isolation (106), equipment v2 (85), and exported-world smoke; Windows/Linux exports passed.
- Public release rebuild also validates launcher, export, saves and SHA-256 ZIP integrity before the release tag is published.
