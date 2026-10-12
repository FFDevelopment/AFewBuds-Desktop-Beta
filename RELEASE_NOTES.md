AFewBuds Desktop Beta 0.16.0-beta.17 — Production Duty & Wall-Mounted Equipment Hotfix

VERIFIED SOURCE
- FFDevelopment/afewbuds-3d-prototype main @ 30dfabae98cd5e8c58b9a597953c792a7ae5aea2
- Complete Godot gameplay/test suite, Windows/Linux exports and exported-world smoke passed: https://github.com/FFDevelopment/afewbuds-3d-prototype/actions/runs/38200776186

NIGHTLY PRODUCTION DUTY
- Production workers no longer lose their intended duty assignment permanently when their nightly wage comes due before the dealer drop-off is settled.
- If wages cannot be paid at closeout, the worker pauses instead of working unpaid. Once sufficient cash is available and safety restrictions permit, the owed wage is paid once and the previously active shift resumes automatically.
- Explicitly sending someone home remains off duty. Heat-related lockdowns, arrests and unpaid bail are not overridden.
- Existing house and apartment production roles, pay, crops, workers, automation, inventory and saved duty choices stay intact.

FURNITURE ARRANGEMENT
- Mounted auto-waterers and ventilation units are selectable while looking at them in walk-around furniture arrangement.
- Target the equipment at its actual elevated world location, not ground level. Selection remains restricted to the correct property and floor (including house basement).
- The arrangement controls support moving or picking up a mounted unit without altering existing ownership, upgrade level or saved placement.

RELEASE SAFETY
- Mobile and desktop share the same payroll logic; this desktop beta uses the desktop-tested source.
- Public release independently tests updater behavior, builds launcher, reruns Godot gameplay tests, verifies Windows/Linux exports, checks file hashes and publishes an update without changing the save directory or login identity.
