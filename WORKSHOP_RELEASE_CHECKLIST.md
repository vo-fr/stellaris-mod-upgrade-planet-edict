# Steam Workshop release checklist — Stellaris 1.9.1

Status: **Release candidate prepared locally; not published on Steam.**

## Prepared

- Seven language files, with the corrected German description
- Local install archive with `UpgradePlanetEdict191.mod`, mod folder, and `descriptor.mod`
- Square cover image named `thumbnail.jpg` and referenced in both descriptors
- English Workshop description (`STEAM_WORKSHOP_DESCRIPTION.txt`)
- Workshop upload procedure documented below

## Required before public release

1. **Reconcile source**: The edict script in the locally prepared release candidate is 6,478 bytes (SHA-256 `f1cb563071769e4bc91308cc0448f0dfb29d0a4ee3cf32942a868f91da4047a6`). The GitHub version differs; replace it with the exact packaged, tested script before tagging a release. Do not describe this repository as matching the binary until done.
2. Add the cover image and descriptors from the local candidate to the repository and create a matching GitHub release `v1.0.0`.
3. Install the candidate into `Documents/Paradox Interactive/Stellaris/mod/` and run Stellaris **1.9.1**, with older variants disabled. Test edict behavior and localisation.
4. In the Stellaris 1.9.1 launcher: **Mods → Mod Tools → Upload Mod**, select the local mod, **Fetch Info** if available, then **Upload**.
5. Review the resulting Steam Workshop item, ensure it is hidden during review, add description and screenshots, then change visibility to **Public** only after approval.
6. Preserve the assigned `remote_file_id` for future updates.

The GitHub repository is a public code repository, **not** evidence that the Steam item is live.
