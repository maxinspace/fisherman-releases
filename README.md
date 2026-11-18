# Fisherman

A sound- and vision-based fishing assistant for World of Warcraft, for Windows 10/11.

**[Download the latest installer](https://fisherman.maxlari.dev/download)** · [Website](https://fisherman.maxlari.dev)

> **Disclaimer.** Automating gameplay is against the World of Warcraft Terms of Use and can get an account suspended.
> Fisherman is an independent tool, not made, endorsed or supported by Blizzard Entertainment. Use it at your own risk.

This repository only hosts the installers. The source code is private. Checksums are at https://fisherman.maxlari.dev/checksums.txt

## Install

1. Download and run `Fisherman-Setup.exe`.
2. Windows may show "Windows protected your PC", because the installer is not code-signed yet. Click **More info**, then **Run anyway**.
3. Compare the file's SHA-256 with the checksums page if you want to check it is the genuine file:

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

Fisherman is free to try: every feature works, but each fishing run stops after 30 minutes. A lifetime license for one PC (150 Telegram Stars, bought once in our bot from the app's License page) removes the limit. Refund within 7 days with `/refund`; moving to a new PC with `/reset`. There is also a Donate page in the app.
