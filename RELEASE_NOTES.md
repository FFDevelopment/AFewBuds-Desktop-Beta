AFewBuds Desktop Beta 0.16.0-beta.11 — Landing Collision & Safe Recovery Hotfix

Source: FFDevelopment/afewbuds-3d-prototype @ c5dfc410dd3fc2c697e8f312f507e45f2f2ad131 (hotfix isolated from unfinished mission and character creator branches).

- Apartment 201 and 301 on the starter building side fire escape now have full-height, non-interactive solid door collision. Exterior landings, roof stair route, handrails, apartment window dressing and original NPC entrances remain intact.
- Added UNSTUCK · RETURN TO SAFE SPOT to Pause, accessible via keyboard, controller and touch UI. Recovery checks the last verified safe grounded checkpoint or an approved nearby anchor with the same player capsule and a support ray, rather than teleporting through other property walls.
- 25-second cooldown and velocity reset prevent repeated teleporting and preserve pause control. Recovery saves only the corrected position through existing career save logic.
- Preserve property ownership, money, furniture, workers, inventory, genetics, story, save schema, cloud account/session protocol, and previous beta.10 NPC/door pacing and graphics quality presets.
- Unfinished Mission & Story Engine and future customizable character changes are excluded.

Release gating: headless Godot import, live physics door/raycast and recovery tests, complete gameplay/save tests, exported Windows/Linux runtime, launcher update/rollback tests, Windows launcher smoke, SHA-256 package validation. The official launcher will select v0.16.0-beta.11 when published. Old stand-alone executables do not auto-update.
