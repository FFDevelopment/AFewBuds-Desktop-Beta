AFewBuds Desktop 0.16.0-beta.9

Based on the tested desktop beta.8 source (not the older prototype main branch).
Candidate validation: https://github.com/FFDevelopment/afewbuds-3d-prototype/actions/runs/37984122772

- Fix non-custom NPCs such as Tyler appearing inside Malik's model: generic door managers now copy only the default primitive rig and use their own skin/face, never embedded custom GLB avatars.
- Clear leftover Malik/Rod/Kobi character attachments when changing a production worker to a non-custom identity.
- Keep Agent Reeves permanently visible through Contacts after the protection balance is fully paid.
- At zero Heat, display the disabled optional paid-favor control with an explanation; text conversations and private visit scheduling remain available.
- With some Heat and a positive paid-off Reeves relationship, optional paid favors reduce Heat and count toward the existing Make the Call milestone without reopening recurring debt.
- Allow Reeves to stop by for a friendly check-in after payoff; talking or declining the visit does not reinstate payments.
- Preserve existing beta.8 gameplay: per-property computers, workers, tent and ventilation settings, light use, furniture previews/free placement, controller support, saving, account sessions, packing, and other progression.

No intentional account/career, inventory or upgrade reset. The release workflow must pass the complete desktop tests, exported runtime smoke checks and package validation before publication.