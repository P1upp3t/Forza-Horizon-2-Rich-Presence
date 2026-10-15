<p align="center"><a href="https://puppetzim.itch.io/fh2-discord-presence"><b>View on itch.io</b></a> · <a href="https://ko-fi.com/puppetzim"><b>Support on Ko-fi</b></a></p>
<h2 align="center"><a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/download/v1.3.1/FH2-Presence-v1.3.1-Windows-x64.zip">⬇ Free download · Windows x64</a></h2>

<p align="center"><b>Azimuth 0.9.9:</b> <a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/download/v1.3.1/FH2-Presence-v1.3.1-Windows-x64.zip">v1.3.1</a> · <b>Azimuth 0.9.7:</b> <a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/download/v1.0.0/FH2-Presence-v1.0.0-Windows-x64.zip">v1.0.0</a></p>



<p align="center"><a href="README.md">English</a> · <a href="docs/translations/README.pt-BR.md">Português (Brasil)</a> · <a href="docs/translations/README.zh-CN.md">简体中文</a> · <a href="docs/translations/README.hi.md">हिन्दी</a> · <a href="docs/translations/README.es.md">Español</a> · <a href="docs/translations/README.fr.md">Français</a> · <a href="docs/translations/README.ar.md">العربية</a> · <a href="docs/translations/README.bn.md">বাংলা</a> · <a href="docs/translations/README.ru.md">Русский</a></p>

<p align="center">
  <img src="FH2-Presence.png" alt="FH2 Discord Presence icon" width="112" />
</p>

<h1 align="center">Forza Horizon 2 — Discord Rich Presence</h1>

<p align="center">
  Your car. Your race. Your Horizon journey, on Discord.
</p>

<p align="center">
  <a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/latest"><b>Download for Windows</b></a> ·
  <a href="https://ko-fi.com/puppetzim">Support on Ko-fi</a> ·
  <a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues">Report a bug</a>
</p>

<p align="center">
  <a href="https://ko-fi.com/puppetzim">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Support FH2 Discord Presence on Ko-fi" height="52" />
  </a>
  <br />
  <sub><b>Free to use. Support is optional.</b> Your support helps keep the project moving.</sub>
</p>

A **free Windows companion** for the Xbox One version of **Forza Horizon 2 running through Azimuth**. Share your current vehicle, location, race progress and in-game activities through Discord Rich Presence.

**All features are free. Donations are optional.** This repository hosts official downloads, documentation and issue tracking. The source code is private.

## New in v1.3.1

Compact mode keeps the preview and main controls in a smaller window. After painting or upgrades, the panel warns when no newer saved thumbnail has appeared; if the appearance changed, try reselecting the car. With local history enabled, closing Azimuth shows the recorded session time and cars used.

Includes all v1.3.0 features below. [Read the release notes](CHANGELOG-v1.3.1.txt).

## New in v1.3.0

Keep the app in the Windows tray, switch between Presence profiles, and choose whether to show the session timer. The delivery preview separates the next payload from the last activity accepted by Discord.

First-use setup checks your Azimuth folder and Discord. Optional local history records session time and cars on your PC, keeps up to 50 sessions and can be deleted in the panel. It is off by default.

## New in v1.2.0

- **Connection checks:** clear status for Azimuth, Discord, Presence and game data, with useful recovery actions.
- **Automatic shutdown:** optional stop after Azimuth closes. The panel stays open; starting Presence stays manual.
- **Privacy controls:** independently hide vehicle/thumbnail, approximate region or race details in Discord and the preview.
- **Version checks:** manually check official releases against the installed Azimuth version. No automatic downloads or installation.
- **Bug reports:** preview and save a local TXT diagnostic report. It excludes logs, saves, player data, credentials, paths and vehicle/location/race details; nothing is sent automatically.

All five controls are translated in the nine interface languages. The new features were tested, and the installed build was checked live on **Azimuth 0.9.9 / FH2 1.0.0.64**. Racing features still need fresh validation on 0.9.9; future builds and the recent Extra Options update are not confirmed compatible. Use legacy v1.0.0 for Azimuth 0.9.7.

Hiding a vehicle prevents new uploads. Already-started uploads may finish, and previously hosted temporary images cannot be revoked by the companion.

## Features

| Feature | What appears on Discord |
| --- | --- |
| Vehicle cards | Your current car, model year and saved thumbnail, with its class and performance index drawn on the image. |
| Appearance updates | Saved paint and wheels when the game provides a new thumbnail. Cards are regenerated when you select or reselect a car. |
| Open world | Your approximate region and current vehicle. |
| Racing | Position, total drivers, circuit laps or sprint progress with two decimal places, plus event information when available. |
| Activities | Icons for the world map, photo mode, pause, Festival, garage, upgrades, painting and Autoshow. |
| Race results | A temporary victory or race-completed status after finishing. |
| Launch Azimuth | Open `azimuth.exe` directly from the app with **Launch FH2 + Presence**, starting the launcher and Presence together. |
| Desktop interface | A Horizon-inspired control panel, live preview and adjustable local reading rate: 1, 2 or 4 Hz. |

Activity labels stay on the small icon and its tooltip, keeping the main presence text focused on your car and session.

## Download & installation

### Before you start

Get Azimuth from [**Almost There Games on itch.io**](https://almost-there-games.itch.io/azimuth). Azimuth is a separate project with its own requirements and terms.

**This project distributes only the Rich Presence companion.** We do not provide Forza Horizon 2, DLCs, game files or license keys. You must obtain your own legitimate game copy and comply with the applicable license terms. Donations support this companion; they do not purchase the game, grant a game license or fund access to game files.

1. Download **FH2-Presence-v1.3.1-Windows-x64.zip** from the [latest release](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/latest).
2. Extract the `rich-presence` folder **next to `azimuth.exe`**.
3. Open the **Discord desktop app** and sign in.
4. Run **FH2 Presence.exe** and choose **Start Presence** or **Launch FH2 + Presence**.
5. To display custom vehicle cards, enable **Automatic Thumbnails** in **Preferences**.

```text
Your game folder/
├── azimuth.exe
├── data/
└── rich-presence/
    ├── FH2 Presence.exe
    ├── README.txt
    ├── LICENSE.txt
    └── ...
```

**Requirements:** Windows 11 x64, Microsoft Edge WebView2 Runtime, Discord desktop and your own game installation. **Python is not required.** The program does not ask for your Discord password, bot token or client secret.

### Updating

Stop Presence and choose **Exit app** before replacing the executable; closing the window can keep the app in the tray. Keep `config.json` and `runtime/` to preserve your preferences and image cache. Both are created locally on first use.

## Languages

English is the default. You can switch to **Brazilian Portuguese, Simplified Chinese, Hindi, Spanish, French, Arabic, Bengali or Russian**, or use the Windows language setting.

Translations are included locally. Vehicle, location and event names are preserved.

## Privacy & vehicle images

- The companion reads the running game and the latest committed local player database. It **does not write to game memory or saves**.
- Automatic image hosting is **off by default**.
- If enabled, only generated vehicle cards are uploaded to **Uguu** as public, temporary PNG links for Discord to display. Cards can show the car's appearance, name, class and performance index.
- Saves, logs and the player database are **not uploaded**. Translations do not use an online service.
- Activity icons, manufacturer logos and the game cover load from external hosts.

## Compatibility & known limits

Use **v1.0.0 for Azimuth 0.9.7** or **v1.3.1 for Azimuth 0.9.9**, with **FH2 1.0.0.64**. On 0.9.9, vehicle name, class/PI, thumbnail, region, pause and open-world presence have been checked live. Racing modes still need a fresh validation on 0.9.9.

- Discord updates have a **minimum 15-second send interval**, independent of the local reading rate. Image hosting and Discord caching can add delay.
- Regions are approximate. New paint or wheel images depend on a thumbnail saved by the game.
- [Extra Options](https://github.com/RokkuDayo/ForzaHorizon2_ExtraOptions) was used during investigation and is not called by the companion. A full test session with that mod disabled is still pending.
- Activity artwork comes from several Forza editions. Pause currently uses a Twemoji fallback.

## Support the project

[![Support on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/puppetzim)

If you enjoy the app, you can [leave an optional donation on Ko-fi](https://ko-fi.com/puppetzim). Your support helps with maintenance, compatibility work and bug fixes.

**Donating is never required to download the app or use a feature.** Donations do not include a copy of the game or guarantee compatibility with an untested build.

## Bugs & feedback

[Open an issue](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues) with your game and Azimuth versions, what happened and what you expected. Review any log before attaching it. Please do not upload saves, credentials or game files.

## License & credits

The application is **freeware with private source code**, not an MIT-licensed project. See [LICENSE.txt](LICENSE.txt) for usage terms.

Third-party software and artwork retain their own licenses and rights. See [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) and [FORZA-ICON-SOURCES.txt](FORZA-ICON-SOURCES.txt).

[Forza Horizon 2 Extra Options](https://github.com/RokkuDayo/ForzaHorizon2_ExtraOptions) helped during investigation. This project does not distribute that mod, the game or save files.

An independent fan project by **Puppet / P1upp3t**. Not affiliated with Microsoft, Xbox, Playground Games, Turn 10, Discord or Azimuth.

