# FH2 Discord Presence v1.4.1

A small update to make interruptions less frustrating. If game data goes missing for 15 seconds, Presence clears the old activity instead of leaving an outdated car or race on Discord. Brief interruptions are tolerated, and updates resume when the data returns.

- **Discord recovery:** Presence reconnects automatically while it is running, with spaced retries. It also notices Discord restarts when your activity has not changed.
- **Clearer connection help:** the panel shows one useful next step at a time, without repeating the main controls.
- **Azimuth 0.9.10 recognition:** the app now recognizes 0.9.9 and 0.9.10, so the confirmed hotfix no longer triggers an unconfirmed-version warning.
- **Better startup errors:** the message explains the type of failure and can open the local error-report folder. WebView2 is only mentioned when the error identifies a missing runtime. Review the report before sharing it.

The connection guidance is available in all nine interface languages. Starting Presence remains manual.

Works with Azimuth 0.9.9 and 0.9.10 / FH2 1.0.0.64. Use legacy v1.0.0 for Azimuth 0.9.7. Later Azimuth versions and the recent Extra Options update are not confirmed compatible.

Download **FH2-Presence-v1.4.1-Windows-x64.zip**. Stop Presence and choose Exit app before updating. Replace the files in rich-presence while keeping config.json and runtime. Start Presence again when ready.

Requires Discord desktop and your own legitimate game installation. Python is not required. All features and downloads are free; support is optional. Source code remains private. No game, DLC, keys, saves or personal configuration are included.

[App page](https://puppetzim.itch.io/fh2-discord-presence) · [Optional support](https://ko-fi.com/puppetzim) · [Report a bug](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues)

## Screenshots

The installed v1.4.1 panel, showing the single connection step when Presence is stopped:

![Connection guidance](https://raw.githubusercontent.com/P1upp3t/Forza-Horizon-2-Rich-Presence/main/docs/images/v1.4.1/FH2-Presence-v1.4.1-Connection-help.jpg)

Discord activity screenshot supplied by Puppet; profile details and unrelated activity are blurred:

![Discord activity](https://raw.githubusercontent.com/P1upp3t/Forza-Horizon-2-Rich-Presence/main/docs/images/v1.4.1/FH2-Discord-v1.4.1-Redacted.png)
