# Chief Scout: Best Player Finder

Chief Scout is a native mod for **Teamfight Manager 2** that helps you find the best players in your current save.

It analyzes players, free agents, transfer targets, potential, stats, upgrade value, and recommendation tags.

## Versions

There are currently two Chief Scout builds:

| Teamfight Manager 2 version |                                                                           Mod version | Build                    | Status     |
| --------------------------- | ------------------------------------------------------------------------------------: | ------------------------ | ---------- |
| 0.4.13                      | [v1.0.5](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.1.0.5-tfm2-0.4.13) | Chief Scout: HTML Report | Compatible |
| 0.4.12 rollback             |  [v1.0.4](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v1.0.4-tfm2-0.4.12) | Legacy Chief Scout       | Stable     |

## Chief Scout: HTML Report

**Chief Scout: HTML Report** is the compatibility version for **Teamfight Manager 2 0.4.13**.

Because dynamic in-game text rendering became unstable in TFM2 0.4.13, this version uses a small in-game launcher and opens the full scouting panel as a local HTML report in your browser.

Use this version if you are playing on **Teamfight Manager 2 0.4.13**.

Release:

[Download Chief Scout: HTML Report v1.0.5 for TFM2 0.4.13](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.1.0.5-tfm2-0.4.13)

## Legacy Chief Scout

The legacy Chief Scout build is intended for the **Teamfight Manager 2 0.4.12 rollback** version.

It uses the old full in-game UI.

Use this version only if you are playing on the 0.4.12 rollback branch.

Release:

[Download Chief Scout v1.0.4 for TFM2 0.4.12](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v1.0.4-tfm2-0.4.12)

## Steam Workshop

Steam Workshop is the recommended installation method for most players.

Legacy Workshop page:

[Subscribe on Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3741344550)

Use manual GitHub releases only if you need a specific mod build for a specific Teamfight Manager 2 game version.

## Manual installation: Chief Scout HTML Report / TFM2 0.4.13

1. Download the **Chief Scout: HTML Report v1.0.5 for TFM2 0.4.13** release archive.
2. Open the Teamfight Manager 2 game folder.
3. Open or create the `mods` folder.
4. Extract the `scout_assistant_html` folder into `mods`.

Final path should look like this:

```text
Teamfight Manager 2/mods/scout_assistant_html/mod.mod_info
```

Do not rename the `scout_assistant_html` folder.

## Manual installation: Legacy Chief Scout / TFM2 0.4.12 rollback

1. Download the **Chief Scout v1.0.4 for TFM2 0.4.12** release archive.
2. Open the Teamfight Manager 2 game folder.
3. Open or create the `mods` folder.
4. Extract the `scout_assistant` folder into `mods`.

Final path should look like this:

```text
Teamfight Manager 2/mods/scout_assistant/mod.mod_info
```

Do not rename the `scout_assistant` folder.

## Important note

Do not install or enable **Chief Scout: HTML Report** together with the legacy **Chief Scout** version.

The HTML Report build uses a separate mod ID and DLL name, so it should not replace the legacy build, but both mods add a Chief Scout entry to the game UI and may conflict if enabled at the same time.

## Source code

This repository is used for archived release builds and compatibility notes.

The source code is not published here.
