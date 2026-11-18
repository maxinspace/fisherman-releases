# Fisherman

A sound- and vision-based fishing assistant for World of Warcraft, for Windows 10/11.
It listens for the bobber splash, finds the bobber on screen, clicks it, loots, re-applies your lure on a timer and casts again.

**[Download the latest installer](https://github.com/maxinspace/fisherman-releases/releases/latest/download/Fisherman-Setup.exe)** · [All versions and checksums](https://github.com/maxinspace/fisherman-releases/releases) · [Website](https://maxinspace.github.io/fisherman-releases/)

> **Disclaimer.** Automating gameplay is against the World of Warcraft Terms of Use and can get an account suspended.
> Fisherman is an independent tool, not made, endorsed or supported by Blizzard Entertainment. Use it at your own risk.

This repository only hosts the installers and the landing page. The source code is private.

## Install

1. Download and run `Fisherman-Setup.exe`.
2. Windows may show "Windows protected your PC", because the installer is not code-signed yet. Click **More info**, then **Run anyway**.
3. Compare the file's SHA-256 with the one in the release notes if you want to check it is the genuine file:

   ```powershell
   Get-FileHash .\Fisherman-Setup.exe
   ```

## Requirements

- Windows 10/11, 64-bit. The app asks for administrator rights so it can send input to WoW.
- WoW in **Windowed (Fullscreen)**, sound on, Master volume around 50%.
- In WoW: Interface > Controls > **Auto Loot** on.
- Fishing on key `1` and your lure on key `2` (changeable in the app).

## Using it

Open Fisherman, click **Quick Setup** and switch to WoW within 5 seconds. Press `F9` to start and `Space` to stop everything. The in-app **How to** page covers the rest, including troubleshooting.

Your settings live in `%APPDATA%\Fisherman`. Uninstall from Windows Settings > Apps; the uninstaller asks whether to delete your settings too.

## Support

The project is supported by donations: there is a Donate page inside the app.
