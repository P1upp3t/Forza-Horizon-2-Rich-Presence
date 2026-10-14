FH2 DISCORD PRESENCE
====================
A free Windows companion for Forza Horizon 2 running through Azimuth.

Show your current car, location and race progress on Discord, with a desktop
interface inspired by the Horizon menus. Donations are optional: all features
remain free.

FEATURES
- Current vehicle, model year and manufacturer.
- Vehicle thumbnail with its class and performance index drawn on the image.
- Card regeneration when selecting a car, including reselecting the same car.
- Saved paint and wheel appearance when the game provides an updated thumbnail.
- Open-world regions, map, pause, photo mode and Festival activity icons.
- Garage, upgrades, painting and Autoshow activity detection.
- Race position, laps, sprint progress with two decimal places and finish state.
- Event and championship information when available.
- English by default, plus Brazilian Portuguese, Simplified Chinese, Hindi,
  Spanish, French, Arabic, Bengali and Russian. Optional Windows language choice.
- Adjustable local reading rate: 1, 2 or 4 updates per second.

INSTALLATION
1. Download the Windows release ZIP from this repository's Releases page.
2. Extract the rich-presence folder next to azimuth.exe. The layout must be:

   Your game folder/
       azimuth.exe
       data/
       rich-presence/
           FH2 Presence.exe
           README.txt
           LICENSE.txt
           THIRD-PARTY-NOTICES.txt

3. Open the Discord desktop application and sign in.
4. Open FH2 Presence.exe. Choose Start Presence, or Launch FH2 + Presence.
5. If you want custom car cards, enable Automatic Thumbnails in Preferences.

Python is not required for the executable. Windows 10/11 x64 and Microsoft
Edge WebView2 Runtime are required for the desktop interface.
No Discord password, bot token or client secret is needed by this program.

UPDATING
Close the interface and stop Presence before replacing the executable.
Keep config.json and runtime/ to preserve your preferences and image cache.
These files are created automatically and are not included in public releases.

PRIVACY AND IMAGE HOSTING
The companion reads the running game and the latest committed local player
database. It does not modify game memory or save files.
Automatic Thumbnails is disabled by default. When enabled, only generated car
thumbnail cards are uploaded to Uguu as public, temporary PNG links, so Discord
can display them. Saves, logs and the player database are not uploaded.
The card can contain the vehicle name, appearance, class and performance index.
Icons, fallback logos and the cover image are loaded from external hosts.
Translations are included locally; no translation service is used.

KNOWN LIMITS
Tested with FH2 1.0.0.64 and Azimuth 0.9.7 on the development PC. Other builds
may use different memory layouts and are not confirmed compatible.
Geographic regions are approximate. A new paint or wheel appearance needs a
thumbnail saved by the game; the companion cannot invent missing thumbnails.
Discord changes have a minimum send interval of 15 seconds, independently of
the local reading rate. Public image hosts and Discord image caching can add delay.
Extra Options was used during investigation and is not called by the program;
a full validation session with that mod disabled has not yet been completed.
Most activity icons are original Forza artwork from several game editions;
the pause icon currently uses a Twemoji fallback. See the source credits.

SOURCE CODE AND FREE USE
The source code is private. This public repository contains downloads,
documentation and issue tracking only. The application is free to use;
it is not licensed under MIT. See LICENSE.txt for the binary usage terms.

BUG REPORTS
Use GitHub Issues. Include the game and Azimuth versions, the activity that
failed and the expected result. Review logs before attaching them and never
share saves, credentials or your complete game installation.

SUPPORT
The program is free. Optional donations support continued development and do
not unlock features or include the game.
Support the project: https://ko-fi.com/puppet91192
Official downloads: https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases

CREDITS
Independent fan project; not affiliated with Microsoft, Xbox, Playground Games,
Turn 10, Discord or Azimuth. Game files are not distributed with this project.
Forza artwork, car manufacturer marks and other third-party assets belong to
their respective owners. See THIRD-PARTY-NOTICES.txt and FORZA-ICON-SOURCES.txt.
