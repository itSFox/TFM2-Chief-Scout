# Chief Scout: Best Player Finder

Chief Scout is a scouting helper mod for **Teamfight Manager 2** that helps you find better players in your current save.
It analyzes free agents, transfer targets, possible upgrades, your own roster, potential, stats, role fit, upgrade value, and recommendation tags.
The current live-compatible build is **Chief Scout: HTML Report v2.0.0** for **Teamfight Manager 2 0.4.14**.

## Versions

| Teamfight Manager 2 version |                                                                           Mod version | Build                    | Status              |
| --------------------------- | ------------------------------------------------------------------------------------: | ------------------------ | ------------------- |
| 0.4.14                      | [v2.0.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.0.0-tfm2-0.4.14) | Chief Scout: HTML Report | Current             |
| 0.4.14                      | [v1.0.6](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.1.0.6-tfm2-0.4.14) | Chief Scout: HTML Report | Archived            |
| 0.4.13                      | [v1.0.5](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.1.0.5-tfm2-0.4.13) | Chief Scout: HTML Report | Archived            |
| 0.4.12 rollback             |  [v1.0.4](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v1.0.4-tfm2-0.4.12) | Legacy Chief Scout       | Stable legacy build |

## Chief Scout: HTML Report v2.0.0

**Chief Scout: HTML Report v2.0.0** is the current compatibility version for **Teamfight Manager 2 0.4.14**.
This version uses a small in-game launcher and opens the full scouting report as a local HTML page in your browser.
The report was redesigned around a clearer scouting workflow and includes:

* New Scorer v1, a new role-aware scoring model
* Classic scorer toggle, so you can compare the old and new scoring logic
* separate Role Score and Prospect Score
* Compact and Full view modes
* score breakdowns with strengths, weak spots, role-specific reasons, and confidence notes
* roster needs analysis
* best available upgrade per role
* role-specific archetypes
* improved filters and sorting
* improved localization strings
* support for 14 languages
  Use this version if you are playing on **Teamfight Manager 2 0.4.14**.
  Release: [Download Chief Scout: HTML Report v2.0.0 for TFM2 0.4.14](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.0.0-tfm2-0.4.14)

## Older HTML Report builds

Older HTML Report builds are kept for compatibility and archive purposes.

### TFM2 0.4.14 / v1.0.6

Use this version only if you specifically need the previous 0.4.14 HTML Report build.
Release: [Download Chief Scout: HTML Report v1.0.6 for TFM2 0.4.14](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.1.0.6-tfm2-0.4.14)

### TFM2 0.4.13 / v1.0.5

Use this version only if you are still playing on **Teamfight Manager 2 0.4.13**.
Release: [Download Chief Scout: HTML Report v1.0.5 for TFM2 0.4.13](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.1.0.5-tfm2-0.4.13)

## Legacy Chief Scout

The legacy Chief Scout build is intended for the **Teamfight Manager 2 0.4.12 rollback** version.
It uses the old full native in-game UI.
Use this version only if you are playing on the 0.4.12 rollback branch.
Release: [Download Chief Scout v1.0.4 for TFM2 0.4.12](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v1.0.4-tfm2-0.4.12)

## Steam Workshop

Steam Workshop is the recommended installation method for most players.
Workshop page for the current HTML Report build: [Subscribe to Chief Scout: HTML Report on Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3751000684)
Legacy Workshop page: [Chief Scout: Best Player Finder legacy Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=3741344550)
Use manual GitHub releases only if you need a specific mod build for a specific Teamfight Manager 2 game version.

## How to use Chief Scout: HTML Report

1. Enable the mod and restart the game.
2. Start or load a save.
3. Click **Chief Scout: HTML Report** in the left-side menu.
4. Click **Refresh database**.
5. Click **Open HTML report**.
6. Use the browser report to search, filter, sort, compare scorers, and inspect recommendations.

## Manual installation: Chief Scout HTML Report v2.0.0 / TFM2 0.4.14

1. Download the **Chief Scout: HTML Report v2.0.0 for TFM2 0.4.14** release archive.
2. Open the Teamfight Manager 2 game folder.
3. Open or create the `mods` folder.
4. Extract the `scout_assistant_html` folder into `mods`.
   Final path should look like this:

```text
Teamfight Manager 2/mods/scout_assistant_html/mod.mod_info
```

Do not rename the `scout_assistant_html` folder.

## Manual installation: older HTML Report builds

Older HTML Report builds use the same mod folder name:

```text
scout_assistant_html
```

Final path should look like this:

```text
Teamfight Manager 2/mods/scout_assistant_html/mod.mod_info
```

Do not rename the `scout_assistant_html` folder.
Make sure you install only one HTML Report version at a time.

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

## Why HTML?

The current HTML Report version is intentionally external HTML instead of a full native in-game panel.
This keeps Chief Scout compatible with Teamfight Manager 2 0.4.14 while still providing a full scouting interface with filters, sorting, scoring explanations, and multilingual UI.

## Source code

This repository is used for archived release builds and compatibility notes.
The source code is not published here.
