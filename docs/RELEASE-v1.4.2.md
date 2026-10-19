# FH2 Discord Presence v1.4.2

Your upgrades now show up properly on the vehicle card. Presence reads the current class and performance index from your active car, including installed upgrades, instead of relying on the earlier car/garage reading.

- **Current class and PI:** the card follows the car's prepared build rather than its factory specification.
- **No misleading fallback:** if the current reading cannot be confirmed, class and PI are left unavailable instead of displaying factory numbers as current.
- **Safer car changes:** mismatched or changing vehicle data is rejected while the game switches cars.

This is a small vehicle-data fix. Your preferences and existing privacy controls still apply. Car pictures can take longer to refresh because they depend on a thumbnail saved by the game and Discord's image cache.

For FH2 1.0.0.64 running through Azimuth 0.9.9 / 0.9.10. Use legacy v1.0.0 for Azimuth 0.9.7. Later Azimuth versions and the recent Extra Options update are not confirmed compatible.

Download **FH2-Presence-v1.4.2-Windows-x64.zip**. Stop Presence and choose Exit app before updating. Replace the files in rich-presence while keeping config.json and runtime, then start Presence again when ready.

Requires Discord desktop and your own legitimate game installation. Python is not required. All features and downloads are free; support is optional. Source code remains private. No game, DLC, keys, saves or personal configuration are included.

[Download v1.4.2](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases/tag/v1.4.2) · [App page](https://puppetzim.itch.io/fh2-discord-presence) · [Optional support](https://ko-fi.com/puppetzim) · [Report a bug](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues)

## Screenshot

The installed panel with the current BMW M6 class and PI (A 800), shown while the game is paused.

![Current vehicle class and PI](https://raw.githubusercontent.com/P1upp3t/Forza-Horizon-2-Rich-Presence/main/docs/images/v1.4.2/FH2-Presence-v1.4.2-Current-PI.jpg)
