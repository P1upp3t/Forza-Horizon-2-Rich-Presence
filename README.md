<p align="center">
  <img src="FH2-Presence.png" alt="FH2 Discord Presence icon" width="112" />
</p>

<h1 align="center">Forza Horizon 2 — Discord Rich Presence</h1>

<p align="center">
  Your car. Your race. Your Horizon journey, on Discord.
</p>

<p align="center">
  <a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/latest"><b>Download for Windows</b></a> ·
  <a href="https://ko-fi.com/puppet91192">Support on Ko-fi</a> ·
  <a href="https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues">Report a bug</a>
</p>

<p align="center">
  <a href="https://ko-fi.com/puppet91192">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Support FH2 Discord Presence on Ko-fi" height="52" />
  </a>
  <br />
  <sub><b>Free to use. Support is optional.</b> Your support helps keep the project moving.</sub>
</p>

A **free Windows companion** for the Xbox One version of **Forza Horizon 2 running through Azimuth**. Share your current vehicle, location, race progress and in-game activities through Discord Rich Presence.

**All features are free. Donations are optional.** This repository hosts official downloads, documentation and issue tracking. The source code is private.

## Features

| Feature | What appears on Discord |
| --- | --- |
| Vehicle cards | Your current car, model year and saved thumbnail, with its class and performance index drawn on the image. |
| Appearance updates | Saved paint and wheels when the game provides a new thumbnail. Cards are regenerated when you select or reselect a car. |
| Open world | Your approximate region and current vehicle. |
| Racing | Position, total drivers, circuit laps or sprint progress with two decimal places, plus event information when available. |
| Activities | Icons for the world map, photo mode, pause, Festival, garage, upgrades, painting and Autoshow. |
| Race results | A temporary victory or race-completed status after finishing. |
| Desktop interface | A Horizon-inspired control panel, live preview and adjustable local reading rate: 1, 2 or 4 Hz. |

Activity labels stay on the small icon and its tooltip, keeping the main presence text focused on your car and session.

## Download & installation

1. Download **FH2-Presence-v1.0.0-Windows-x64.zip** from the [latest release](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/latest).
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

**Requirements:** Windows 10/11 x64, Microsoft Edge WebView2 Runtime, Discord desktop and your own game installation. **Python is not required.** The program does not ask for your Discord password, bot token or client secret.

### Updating

Stop Presence and close the interface before replacing the executable. Keep `config.json` and `runtime/` to preserve your preferences and image cache. Both are created locally on first use.

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

Tested on the development PC with **FH2 1.0.0.64** and **Azimuth 0.9.7**. Other builds are not yet confirmed compatible.

- Discord updates have a **minimum 15-second send interval**, independent of the local reading rate. Image hosting and Discord caching can add delay.
- Regions are approximate. New paint or wheel images depend on a thumbnail saved by the game.
- Extra Options was used during investigation and is not called by the companion. A full test session with that mod disabled is still pending.
- Activity artwork comes from several Forza editions. Pause currently uses a Twemoji fallback.

## Support the project

[![Support on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/puppet91192)

If you enjoy the app, you can [leave an optional donation on Ko-fi](https://ko-fi.com/puppet91192). Your support helps with maintenance, compatibility work and bug fixes.

**Donating is never required to download the app or use a feature.** Donations do not include a copy of the game or guarantee compatibility with an untested build.

## Bugs & feedback

[Open an issue](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues) with your game and Azimuth versions, what happened and what you expected. Review any log before attaching it. Please do not upload saves, credentials or game files.

## License & credits

The application is **freeware with private source code**, not an MIT-licensed project. See [LICENSE.txt](LICENSE.txt) for usage terms.

Third-party software and artwork retain their own licenses and rights. See [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) and [FORZA-ICON-SOURCES.txt](FORZA-ICON-SOURCES.txt).

[Forza Horizon 2 Extra Options](https://github.com/RokkuDayo/ForzaHorizon2_ExtraOptions) helped during investigation. This project does not distribute that mod, the game or save files.

An independent fan project by **Puppet / P1upp3t**. Not affiliated with Microsoft, Xbox, Playground Games, Turn 10, Discord or Azimuth.
