# Upgrade Buildings — Stellaris 1.9.1

A lightweight planetary edict to upgrade **mines, power plants and farms** on the selected planet. Built and player-tested for Stellaris **1.9.1 (Boulle)**.

## Features

- Upgrade eligible mines, power plants and hydroponic farms, including basic colony buildings.
- 15 upgrade transitions (basic → tier I and tier I → V for three building families).
- Uses the normal construction queue, mineral costs and build times.
- Checks required technologies and preserves capital-only restrictions for tier V.
- Skips tiles already under construction and leaves other buildings unchanged.
- Works via **Planetary Edicts → Upgrade Buildings**; no console commands or executable modifications.
- Seven localisations: English, German, French, Spanish, Polish, Russian and Brazilian Portuguese.

## Compatibility

**Stellaris 1.9.1 only.** This is a legacy-version mod, not designed for current Stellaris releases. Other mods that replace planetary edicts or building definitions may conflict.

## Manual installation

1. Extract the release archive to `Documents/Paradox Interactive/Stellaris/mod/`.
2. Verify `mod/UpgradePlanetEdict191.mod` and `mod/UpgradePlanetEdict191/common/edicts/upgrade_planet_edict.txt`.
3. Enable **Upgrade Buildings (Stellaris 1.9.1)** in the launcher.
4. Select a planet, open **Planetary Edicts**, and choose **Upgrade Buildings** (translated according to the game language).

## Known limitations

- Only mines, power plants and hydroponic farms are automated; branching upgrade choices are deliberately excluded.
- Only the selected planet is affected.
- The edict is repeatable; already-running construction is skipped.
- The original mod logic was tested in Stellaris 1.9.1; translations other than English/German have not been individually confirmed in-game.

## Version history

**1.0.0 — Workshop-ready candidate**: Retains the player-tested 15 upgrade rules and all seven localisations. Adds publication documentation.

## Credits

Built collaboratively with ChatGPT and tested in Stellaris 1.9.1 by the project owner. Stellaris is a trademark of Paradox Interactive. This is an unofficial community mod.
