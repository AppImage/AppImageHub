---
layout: app

permalink: /DuckStation/
description: Fast-ish PlayStation 1 emulator

icons:
  - DuckStation/icons/48x48/duckstation-qt.png

screenshots:
  - DuckStation/screenshot.png

authors:
  - name: stenzek
    url: https://github.com/stenzek

links:
  - type: GitHub
    url: stenzek/duckstation
  - type: Download
    url: https://github.com/stenzek/duckstation/releases

desktop:
  Desktop Entry:
    Type: Application
    Name: DuckStation Qt
    GenericName: PlayStation 1 Emulator
    Comment: Fast-ish PlayStation 1 emulator
    Icon: duckstation-qt
    TryExec: duckstation-qt
    Exec: duckstation-qt %f
    Terminal: true
    Categories: Game
    X-AppImage-Version: 9f22684
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
