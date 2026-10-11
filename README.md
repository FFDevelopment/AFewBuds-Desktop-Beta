# AFewBuds Desktop Beta

## Windows automatic updates

Use **AFewBuds-Launcher.exe** from the [latest release](https://github.com/FFDevelopment/AFewBuds-Desktop-Beta/releases). The existing launcher checks the same release feed every time it starts and downloads a newer complete, SHA-256-verified Windows beta when available. A beta.11 launcher can update to beta.12 without reinstalling the launcher.

The launcher installs into its own per-user folder and **never clears game saves or logins**. It keeps the previous verified game for rollback if a new build fails to launch. A failed download or offline startup retains the installed build.

**Important:** Opening an older **AFewBuds-3D-Prototype.exe** directly does *not* check for updates. Open the existing launcher instead. Extracted ZIP copies must be updated manually unless started through the launcher. Linux beta ZIPs are also manually updated.

Current desktop release: **0.16.0-beta.12**. Includes the latest tested house operations, furniture-aware NPC navigation and realistic door staff movement, graphics quality presets, and the shared property/item foundations. Gameplay uses the same `AFewBuds-Inventory-Preview` Godot save directory and existing cloud-account protocol as beta.9.

[Download the newest desktop beta](https://github.com/FFDevelopment/AFewBuds-Desktop-Beta/releases)
