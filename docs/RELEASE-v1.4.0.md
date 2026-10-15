# v1.4.0 — a simpler panel and easier privacy controls

This update makes the everyday panel simpler: your Discord preview, connection status and the controls you need are kept together. Profiles, history, updates and troubleshooting are now grouped in collapsible sections in Preferences, so they are there when you need them.

- **Discreet mode:** show just the game, without your car, region, race details or timer. A return button brings back your previous privacy and timer settings without changing your other preferences.
- **Fewer surprises in Preferences:** the app warns about unapplied changes. Restoring defaults shows what will change before filling the form, and the privacy example lets you try the switches locally before saving.
- **A panel that remembers you:** window position and size are kept separately for full and compact views. If a monitor is disconnected, the window fits onto an available screen. Opening the app again brings back the existing panel.
- **Your choice at startup:** the panel can open in the Windows tray. Turn off Start in tray in Preferences if you prefer seeing the window. First-time setup stays visible, and starting Presence remains manual. Closing to the tray also avoids the freeze caused by the earlier close handler.
- **Clearer controls:** keyboard focus is easier to see, compact controls and text are more readable, and Brazilian Portuguese keeps the name Presence.
- **Compatibility guidance:** the panel warns when it cannot confirm your Azimuth version. The help also covers Discord connection problems, delayed updates and cached car images.

Discreet mode affects upcoming activity updates; Discord can take a little time to refresh. Hiding the vehicle prevents new card uploads, but uploads already in progress may finish and existing temporary image links cannot be revoked.

This companion targets Azimuth 0.9.9 with FH2 1.0.0.64. Racing features still need a fresh check on 0.9.9. Future Azimuth versions and the recent Extra Options update are not confirmed compatible. Use legacy v1.0.0 for Azimuth 0.9.7.

Download **FH2-Presence-v1.4.0-Windows-x64.zip**. Stop Presence and exit the app before updating, then replace the files in rich-presence while keeping config.json and runtime. Start Presence again when you are ready. 

Requires Discord desktop and your own legitimate game installation. Python is not required. All features and downloads are free; support is optional. Source code remains private. No game, DLC, keys, saves or personal configuration are included.

[Downloads](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/releases) · [App page](https://puppetzim.itch.io/fh2-discord-presence) · [Optional support](https://ko-fi.com/puppetzim) · [Report a bug](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/issues)


## A look at the new panel

The overview keeps the activity preview and everyday controls together. These captures show the app interface in Brazilian Portuguese.

![Simplified overview with Presence running and Discord connected](https://raw.githubusercontent.com/P1upp3t/Forza-Horizon-2-Rich-Presence/main/docs/images/v1.4.0/FH2-Presence-v1.4.0-Overview.jpg)

Preferences groups stay collapsed until you need them.

![Preferences with optional sections collapsed](https://raw.githubusercontent.com/P1upp3t/Forza-Horizon-2-Rich-Presence/main/docs/images/v1.4.0/FH2-Presence-v1.4.0-Preferences.jpg)

[Frequently asked questions](https://github.com/P1upp3t/Forza-Horizon-2-Rich-Presence/blob/main/docs/FAQ.md)
