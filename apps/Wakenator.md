---
layout: app

permalink: /Wakenator/
description: Wake up your teammates
license: GPL-3.0

icons:
  - Wakenator/icons/256x256/wakenator.png

screenshots:
  - Wakenator/screenshot.png

authors:
  - name: edus44
    url: https://github.com/edus44

links:
  - type: GitHub
    url: edus44/wakenator
  - type: Download
    url: https://github.com/edus44/wakenator/releases

desktop:
  Desktop Entry:
    Name: Wakenator
    Comment: Wake up your teammates
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: wakenator
    X-AppImage-Version: 1.0.2.66
    X-AppImage-BuildId: 69fae3a0-6eeb-11a8-1f74-7d30559ed3d6
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  main: main.js
  homepage: https://github.com/edus44/wakenator
  repository: git@github.com:edus44/wakenator.git
  author:
    name: edus44
    email: eduhhg@gmail.com
  license: GPLv3
  dependencies:
    auto-launch: "^5.0.5"
    debug: "^3.1.0"
    electron-log: "^2.2.14"
    electron-menubar: "^1.0.1"
    electron-updater: "^2.21.10"
---
