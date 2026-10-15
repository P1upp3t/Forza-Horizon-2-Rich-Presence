## New in v1.3.2

- **Assisted updates:** check for a compatible official release, download it and let the app verify the checksum before installing. Installation restarts the panel and keeps a local backup of the previous app and preferences. After an assisted update, you can return to the previous app version from Preferences; your current settings are kept.
- **Export and import preferences:** move your settings and named profiles to another installation without copying the whole app folder. The file excludes game paths, credentials, vehicle images and session history. You can review it before applying it, and importing keeps a local copy of your previous settings. Stop Presence before importing.
- **Optional connection notifications:** Windows can notify you when the Discord connection drops or returns. Brief interruptions are ignored, and notices don't include your car or location. They're off by default and follow your Windows notification settings.
- **Save and apply profiles in one click:** saving a named profile now applies it immediately and keeps the language, reading rate and other settings you've selected in the panel. There's no need to apply it first or save everything twice.

Includes the tray, profiles, session timer, delivery preview, setup checks, local history, compact mode and session recap from v1.3.0 and v1.3.1. The new controls are available in all nine interface languages.

## Compatibility

For **Azimuth 0.9.9 with FH2 1.0.0.64**. Racing support on 0.9.9 still needs a fresh check. Compatibility with future Azimuth versions or the recent Extra Options update isn't confirmed. Use legacy **v1.0.0 for Azimuth 0.9.7**.

Discord activity updates have a minimum 15-second interval. New paint or wheel pictures depend on a thumbnail saved by the game and can take longer to appear in Discord.

## Download and install

Download **FH2-Presence-v1.3.2-Windows-x64.zip** below. You can update directly to this version. Stop Presence and choose **Exit app** before replacing files; closing the window can leave it in the tray. Extract `rich-presence` next to `azimuth.exe`, keeping your existing `config.json` and `runtime` folder.

Requires Windows 11 x64, WebView2 and Discord desktop. Python is not required. Verify the ZIP with `SHA256SUMS.txt`.

The assisted updater is available from this version onward. It only prepares a newer release that explicitly supports your installed Azimuth version. Installing or returning to a previous version stops Presence and restarts the panel; start Presence again when you're ready. Rollback becomes available after an assisted installation.

All features and downloads are free. Source code remains private. No game, DLC, game files, license keys or personal configuration are included. Automatic thumbnail hosting, local history and connection notifications are off by default. Enabling images permits public, temporary car-card uploads; existing image links cannot be revoked by the app.

[App page on itch.io](https://puppetzim.itch.io/fh2-discord-presence) · [Optional support on Ko-fi](https://ko-fi.com/puppetzim) · [Report a bug](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues)
