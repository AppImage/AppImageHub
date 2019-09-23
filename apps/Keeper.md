---
layout: app

permalink: /Keeper/
description: A electron application that shows a webview for keep.google.com

icons:
  - Keeper/icons/900x900/keeper.png

screenshots:
  - Keeper/screenshot.png

authors:
  - name: trinchi
    url: https://github.com/trinchi

links:
  - type: GitHub
    url: trinchi/keeper
  - type: Download
    url: https://github.com/trinchi/keeper/releases

desktop:
  Desktop Entry:
    Name: Keeper
    Comment: A electron application that shows a webview for keep.google.com
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: keeper
    StartupWMClass: Keeper
    X-AppImage-Version: 1.0.1
    Categories: Utility
    X-AppImage-BuildId: 1I8oG0NAW7mqirErkUvjgjAf0LJ
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: src/index.js
  author: David Trinchi
  license: ISC
  repository: https://github.com/trinchi/keeper
  dependencies:
    electron-log: "^3.0.1"
    electron-store: "^2.0.0"
    electron-updater: "^4.0.6"
---
