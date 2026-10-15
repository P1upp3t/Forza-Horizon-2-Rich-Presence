<p align="center"><img src="docs/FH2-Presence.png" alt="FH2 Discord Presence" width="128" /></p>

# FH2 Discord Presence

A free Windows companion for **Forza Horizon 2 on Azimuth**. Share your car, approximate region and in-game activity through Discord Rich Presence.

<a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/latest"><img src="docs/buttons/download-latest.svg" alt="Download latest release" height="48" /></a>&nbsp;&nbsp;<a href="https://ko-fi.com/puppetzim"><img src="docs/buttons/support-kofi.svg" alt="Support on Ko-fi — optional" height="48" /></a>&nbsp;&nbsp;<a href="https://puppetzim.itch.io/fh2-discord-presence"><img src="docs/buttons/itchio.svg" alt="View on itch.io" height="48" /></a>&nbsp;&nbsp;<a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues"><img src="docs/buttons/report-issue.svg" alt="Report an issue" height="48" /></a>

<p align="center"><a href="README.md">English</a> · <a href="docs/translations/README.pt-BR.md">Português (Brasil)</a> · <a href="docs/translations/README.zh-CN.md">简体中文</a> · <a href="docs/translations/README.hi.md">हिन्दी</a> · <a href="docs/translations/README.es.md">Español</a> · <a href="docs/translations/README.fr.md">Français</a> · <a href="docs/translations/README.ar.md">العربية</a> · <a href="docs/translations/README.bn.md">বাংলা</a> · <a href="docs/translations/README.ru.md">Русский</a></p>

## Features

- Vehicle cards with the saved car thumbnail, model year, class and performance index; region, race progress and activity icons when available.
- Privacy controls with a local example, discreet mode with return to the previous profile, saved profiles and an optional session timer.
- A simpler panel, collapsible Preferences, compact mode, remembered window layout and optional startup in the Windows tray.
- Launch Azimuth with Presence, check connections, stop Presence after Azimuth closes and enable optional connection notifications.
- Compatible release checks, assisted updates with a local backup and rollback, and preference export/import.
- Local bug-report previews and optional session history. History is off by default, keeps up to 50 sessions and stays on your PC.
- Nine interface languages and local reading rates of 1, 2 or 4 Hz.

Screenshots and version-by-version changes are in [Releases](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases) and the [itch.io devlog](https://puppetzim.itch.io/fh2-discord-presence/devlog).

## Install & update

Requires **Discord desktop** and your own legitimate game installation. Python is not required. [Get Azimuth](https://almost-there-games.itch.io/azimuth).

1. Choose the download for your Azimuth version: [current release for 0.9.9](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/download/v1.4.0/FH2-Presence-v1.4.0-Windows-x64.zip), or [legacy v1.0.0 for 0.9.7](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/download/v1.0.0/FH2-Presence-v1.0.0-Windows-x64.zip).
2. Extract `rich-presence` next to `azimuth.exe`.
3. Open Discord, run `FH2 Presence.exe` and choose **Start Presence** or **Launch FH2 + Presence**.
4. Enable **Automatic Thumbnails** in Preferences if you want custom vehicle cards.

After first-time setup, the panel can open in the Windows tray. Open it from the tray icon or turn off **Start in tray** in **Preferences → Behaviour and history**. Presence still starts manually.

For a manual update, stop Presence and choose **Exit app** before replacing files. Keep `config.json` and `runtime/`. Assisted updates restart the panel and keep a local backup; rollback becomes available after an assisted installation.

## Compatibility & privacy

The current release supports **Azimuth 0.9.9 / FH2 1.0.0.64**. Racing support on 0.9.9 still needs a fresh check; future Azimuth versions and the recent Extra Options update are not confirmed compatible.

- Discord sends have a minimum 15-second interval. New paint and wheel pictures depend on a thumbnail saved by the game; reselecting the car can help. Hosting and Discord caching may add delay.
- The companion does not modify game memory or saves. Saves, logs and the player database are not uploaded; no Discord password or token is requested.
- Thumbnail hosting is off by default. Enabling it uploads generated car cards to Uguu as public, temporary images. Hiding the vehicle prevents new uploads; uploads already in progress may finish, and existing links cannot be revoked. Activity artwork can load from external hosts.

## Feedback & credits

[Frequently asked questions](docs/FAQ.md) cover connection issues, image caching, updates and privacy.

When reporting a problem, include your game and Azimuth versions, what happened and what you expected. Review the local bug report before attaching it.

All features and downloads are free. Optional support helps fund maintenance and development. This repository hosts downloads, documentation and issue tracking; **source code remains private**.

[Usage terms](docs/LICENSE.txt) · [Third-party notices](docs/THIRD-PARTY-NOTICES.txt) · [Artwork sources](docs/FORZA-ICON-SOURCES.txt).

## Acknowledgements

Thank you to **RokkuDayo**, creator of [Forza Horizon 2 Extra Options](https://github.com/RokkuDayo/ForzaHorizon2_ExtraOptions), for a tool that helped me investigate how the game works.

An independent fan project by Puppet / P1upp3t, not affiliated with Microsoft, Xbox, Playground Games, Turn 10, Discord or Azimuth. No game, DLC, game files or license keys are included; donations do not grant a game license.
