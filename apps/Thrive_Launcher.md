---
layout: app

permalink: /Thrive_Launcher/
description: Thrive Launcher manages downloading Thrive releases

icons:
  - Thrive_Launcher/icons/128x128/thrive-launcher.png

screenshots:
  - Thrive_Launcher/screenshot.png

authors:
  - name: Revolutionary-Games
    url: https://github.com/Revolutionary-Games

links:
  - type: GitHub
    url: Revolutionary-Games/Thrive-Launcher
  - type: Download
    url: https://github.com/Revolutionary-Games/Thrive-Launcher/releases

desktop:
  Desktop Entry:
    Name: Thrive Launcher
    Comment: Thrive Launcher manages downloading Thrive releases
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: thrive-launcher
    StartupWMClass: Thrive Launcher
    X-AppImage-Version: 1.0.3
    Categories: Game
    X-AppImage-BuildId: 1Ec1veSfF3oKjPDQv6g8k0Pg6nA
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Thrive Launcher manages downloading Thrive releases
  main: main.js
  repository: https://github.com/Revolutionary-Games/Thrive-Launcher
  author:
    name: Revolutionary Games
    email: revolutionarygamesstudio@gmail.com
    url: http://revolutionarygamesstudio.com/
  license: MIT
  dependencies:
    feedparser: "^2.2.9"
    jquery: "^3.3.1"
    js-sha3: "^0.8.0"
    mkdirp: "^0.5.1"
    moment: "^2.20.1"
    openpgp: "^4.3.0"
    request: "^2.88.0"
    strip-json-comments: "^2.0.1"
  postinstall: electron-builder install-app-deps
---
