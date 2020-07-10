---
layout: app

permalink: /PreMiD/
description: Discord Rich Presence for websites.

icons:
  - PreMiD/icons/128x128/premid.png

screenshots:
  - PreMiD/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: PreMiD Portable
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: premid
    StartupWMClass: PreMiD Portable
    X-AppImage-Version: 2.0.20
    Comment: Discord Rich Presence for websites.
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Discord Rich Presence for websites.
  version: 2.0.20
  repository: https://github.com/PreMiD/PreMiD
  license: MIT
  dependencies:
    auto-launch: 5.0.5
    discord-rpc: github:discordjs/RPC
    electron-store: 5.1.0
    electron-updater: "^4.2.0"
    socket.io: 2.3.0
---
