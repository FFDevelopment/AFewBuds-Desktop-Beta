AFewBuds Desktop Beta 0.16.0-beta.12 — House Furniture Arrangement Hotfix

Source: FFDevelopment/afewbuds-3d-prototype @ d416ce549cfeb48f51eb557a23f35078c8889c4a, isolated from beta.11's validated game source. Excludes all experimental avatar redesign and Mission & Story Engine development changes.

FIX:
- Home > Phone > Properties > Maple Flats House > ARRANGE FURNITURE is available when an authorized owner is physically inside the house even if Starter Apartment is selected as the main property.
- Primary operation selection no longer blocks furniture placement; actual room presence and property ownership are checked instead.
- House UI opens the existing property-specific furniture manager with Unlock, Move, Pick up and Walk-around Edit Mode controls.
- Remote editing from another property or outside remains blocked; no access is granted to unowned properties.
- House/apartment stock and furniture remain separate. Existing tents, layouts, furnishings, workers, money and career saves are not modified by this hotfix.
- Save schema, cloud identity/session, starter apartment access, Unstuck and stair-landing collision fixes remain unchanged.

QA: property-isolation regression with house owned and apartment-primary career verifies enabled phone button, opening correct property editor, no save or furniture mutations, and remote denial. Full desktop gameplay/save, exported-world and launcher updater/rollback checks must pass before the beta is published.

Windows: Launch the installed AFewBuds Launcher for automatic SHA-256-verified updating to beta.12, without reinstallation. Direct older game executables and Linux ZIP installations require manual update.
