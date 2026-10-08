Desktop Beta 0.14.9-beta.2 fixes false session sign-outs.

- Save conflicts keep the login and pending local progress instead of falsely reporting another active device and signing the player out.
- Saves use the server's atomic session and revision checks; equivalent JSON number formatting no longer changes save fingerprints.
- Incomplete heartbeat responses do not invent a session replacement. Ended-session messages no longer claim another device is active without confirmation.
- Actual ownership and revision conflicts still block stale uploads. Existing careers and backups are preserved.

Download AFewBuds-Windows-Beta.zip and extract it into a new folder. Updates are manual. Keep your existing application data.

This patch is based on the public 0.14.9 beta, with no experimental furniture changes. Source: 57f020c4c942a404fcf17d1e39f3e9d832640050. Publication requires all desktop test suites and the exported-world check to pass.
