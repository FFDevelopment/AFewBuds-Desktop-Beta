# AFewBuds Desktop Beta

[Download the Windows beta](https://github.com/FFDevelopment/AFewBuds-Desktop-Beta/releases/tag/v0.16.0-beta.2)

Choose **AFewBuds-Windows-Beta.zip**, extract the entire ZIP into a folder, and run **AFewBuds-3D-Prototype.exe**. Keep the accompanying files together. A Linux build is also available on the release page.

Sign in with your AFewBuds account to continue your shared career. [Play the matching mobile version](https://ffdevelopment.github.io/afewbuds-beta/). Switching devices pauses the previous session and loads its latest confirmed cloud save. Only one play session can be active per account. Guest careers stay on their device.

Version 0.16.0-beta.2 fixes false session sign-outs: save conflicts preserve the login and local progress, and incomplete session checks no longer report another active device.

## Updating

This beta does **not** include an automatic updater. Download each new release, extract it into a new folder, and launch the new version. Signed-in careers are stored in the cloud. Use Save & Quit before changing versions; do not delete your local application data. Use current desktop and mobile builds together: older builds cannot save to a career after it has enabled the protected shared-session system.

## Controls

Keyboard: E interacts, Shift sprints. Controller: D-pad Up opens the phone, D-pad Right opens the backpack, and pressing L3 toggles sprint while moving forward. Pause contains Settings, Help, and Save & Quit. The first-day guide explains the current gameplay.

## Feedback

[Report a bug](https://github.com/FFDevelopment/AFewBuds-Desktop-Beta/issues) with your version, what happened, and steps to reproduce it. Do not include passwords or session tokens.

## Build provenance

This beta is built and tested from [desktop source commit 98e6383](https://github.com/FFDevelopment/afewbuds-3d-prototype/commit/98e6383515ca423110f5988626a2444df1c07aea). Internal game version: `0.16.0-beta.2`. The release includes SHA-256 checksums and a source archive. This repository distributes beta releases; shared game development remains in the desktop and mobile source repositories.

Version 0.16.0-beta.2 restores desktop station prompts and separates property stock and assigned-worker actions. Opening the house no longer changes apartment inventory ownership. Existing recorded contents and saves are preserved.
