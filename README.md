# Chief Scout: Best Player Finder

Chief Scout is a scouting helper mod for **Teamfight Manager 2** that helps you compare free agents, transfer targets, possible upgrades, your own roster, role fit, potential, stats, roster needs, archetypes, and recommendation tags.

The current builds are **Chief Scout: Best Player Finder v2.3.0** and **Chief Scout: HTML Report v2.3.0** for **Teamfight Manager 2 0.6.0**.

For most players, the native in-game version is recommended. The HTML Report is available as an alternative browser-based report.

## Version navigator

| Teamfight Manager 2 version | Mod version | Build | Status |
| --- | ---: | --- | --- |
| 0.6.0 | [v2.3.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.3.0-tfm2-0.6.0) | Chief Scout: Best Player Finder | Current / recommended |
| 0.6.0 | [v2.3.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.3.0-tfm2-0.6.0) | Chief Scout: HTML Report | Current / alternative |
| 0.5.7 | [v2.1.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.1.0-tfm2-0.5.7) | Chief Scout: Best Player Finder | Archived |
| 0.5.7 | [v2.2.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.1.0-tfm2-0.5.7) | Chief Scout: HTML Report | Archived |
| 0.5.5 | [v2.0.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.0.0-tfm2-0.5.5) | Chief Scout: Best Player Finder | Archived |
| 0.5.5 | [v2.1.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/HTML_v.2.1.0-tfm2-0.5.5) | Chief Scout: HTML Report | Archived |
| 0.5.5 | [v2.0.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.0.0-tfm2-0.5.5) | Chief Scout: HTML Report | Archived |
| 0.5.0 | [v2.0.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.0.0-tfm2-0.5.0) | Chief Scout: Best Player Finder | Archived |
| 0.5.0 | [v2.0.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.0.0-tfm2-0.5.0) | Chief Scout: HTML Report | Archived |
| 0.4.14 | [v2.0.0](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.2.0.0-tfm2-0.4.14) | Chief Scout: HTML Report | Archived |
| 0.4.14 | [v1.0.6](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.1.0.6-tfm2-0.4.14) | Chief Scout: HTML Report | Archived |
| 0.4.13 | [v1.0.5](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v.1.0.5-tfm2-0.4.13) | Chief Scout: HTML Report | Archived |
| 0.4.12 rollback | [v1.0.4](https://github.com/itSFox/TFM2-Chief-Scout/releases/tag/v1.0.4-tfm2-0.4.12) | Legacy Chief Scout | Stable legacy build |

## Chief Scout: Best Player Finder

The native version opens directly inside the game.

Main features:

- New Scorer v1 and Classic scorer toggle
- Role Score and Perspective
- free agents, transfers, upgrades, own roster, and roster needs
- role-specific archetypes and recommendation tags
- score breakdowns and Why explanations
- Compact / Full detail modes
- filters and sorting
- native player profile popup
- player stats, contract data, Solo Rank, development, Mindset, and Style
- 14-language UI
- Stable Mod API support

### Current limitation

The previous **Open in Solo Rank** action is currently unavailable because the Stable Mod API does not expose a function for opening a specific player's game page.

Chief Scout provides its own player profile popup instead. Signing and contract negotiations still use the game's normal recruitment and player management screens.

## Chief Scout: HTML Report

The HTML version uses a small in-game launcher and opens the scouting report as a local page in your browser.

It uses the same main scouting logic as the native version, with a larger report-style interface.

Additional advantages include:

- wider tables and more screen space
- Compact / Full view modes
- player stat previews
- hover previews and click-to-pin stat cards
- support for 14 languages
- the ability to keep the report open alongside the game

## Which version should I use?

Use **Chief Scout: Best Player Finder** if you want the normal in-game panel and tighter integration with the game UI.

Use **Chief Scout: HTML Report** if you prefer a larger browser report and more screen space.

Do not install or enable both versions at the same time.

## Steam Workshop

**Chief Scout: Best Player Finder**  
https://steamcommunity.com/sharedfiles/filedetails/?id=3741344550

**Chief Scout: HTML Report**  
https://steamcommunity.com/sharedfiles/filedetails/?id=3749329216

## Manual installation

Download the release for your game version from the version navigator above.

For the native version, extract:

    scout_assistant

into:

    Teamfight Manager 2/mods/

Final path:

    Teamfight Manager 2/mods/scout_assistant/mod.mod_info

For the HTML version, extract:

    scout_assistant_html

into:

    Teamfight Manager 2/mods/

Final path:

    Teamfight Manager 2/mods/scout_assistant_html/mod.mod_info

Do not rename the mod folders.

## Stable Mod API

The current 0.6.0 builds use the official **Stable Mod API** instead of the older classic native API.

The 0.6.0 compatibility update adapted the Chief Scout launcher to the game's new main menu layout. The scouting and scoring systems were not changed.

## Source code

This repository is used for archived release builds and compatibility notes.

The source code is not published here.
