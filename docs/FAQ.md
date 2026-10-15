# Frequently asked questions

## What do I need?
Discord desktop and your own legitimate game installation. Python is not required. Choose the companion release that matches your Azimuth version.

## Why does Discord update slowly, even at 4 Hz?
The reading rate only controls how often the app checks local game data and refreshes its panel. Discord activity sends have a minimum 15-second interval. Image hosting and Discord caching may add more delay.

## Why does nothing appear on my Discord profile?
Open Discord desktop and sign in, load FH2 through Azimuth, then start Presence in the companion. Check the connection panel for any waiting or disconnected item. In Discord, make sure activity sharing is enabled. After connecting, allow at least one activity update interval. If it still does not appear, stop and start Presence and check that your companion release matches Azimuth.

## Why is my car picture still showing the old paint or wheels?
The companion uses the thumbnail saved by the game. After changing the car, try selecting or reselecting it so the game saves a fresh thumbnail. Even after a new card is uploaded, Discord may keep its previous cached picture for a while.

## How do I update without losing my preferences?
For a manual update, stop Presence and choose Exit app; closing the window can leave it in the tray. Replace the app files while keeping config.json and runtime. An assisted update verifies the official download and keeps a local backup. Rollback becomes available after an assisted installation and preserves your current preferences. Start Presence again when you are ready.

## Which Azimuth release should I use?
The current companion supports Azimuth 0.9.9 with FH2 1.0.0.64. Azimuth 0.9.7 uses legacy companion v1.0.0. Racing support on 0.9.9 still needs a fresh check; future Azimuth builds and the recent Extra Options update are not confirmed compatible. A compatibility warning means the installed Azimuth version is unconfirmed or could not be identified; it does not prove that the game is broken.

## Does the app start or update automatically?
Starting Presence remains manual. Assisted downloads and installation require your choice. You can optionally stop Presence after Azimuth closes and enable Windows connection notices.

## What leaves my PC?
Thumbnail hosting is off by default. Enabling it uploads generated car cards as public, temporary images. Saves, logs and the player database are not uploaded. Hiding the vehicle prevents new card uploads; uploads already in progress may finish, and existing hosted links cannot be revoked. Activity artwork may load from external hosts. The app never asks for your Discord password or token.

## Where do profiles and history go?
Preferences and named profiles stay in config.json. Optional history is off by default, keeps up to 50 sessions locally and can contain car names even when they are hidden from Discord. A preference export excludes game paths, credentials, images and history.

## How do I leave discreet mode?
Choose Return to previous profile to restore the privacy and timer options you used before enabling discreet mode. Language, reading rate and other preferences stay as they are now. You can also choose a profile in Preferences. If the app was already set to game-only before using the shortcut, there is no previous profile to restore.

## Will the app remember my window?
The desktop app keeps separate local window positions and sizes for full and compact views. If a monitor is disconnected, the next opening fits the window onto an available screen. Window layout stays on this PC and is separate from preference exports.

## How do I report a problem?
Include your companion, game and Azimuth versions, what happened and what you expected. You can preview and save a local TXT bug report in Preferences. Review it before attaching it to a GitHub issue; nothing is sent automatically.

[Downloads and release notes](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases) · [Report an issue](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues) · [App page](https://puppetzim.itch.io/fh2-discord-presence)
