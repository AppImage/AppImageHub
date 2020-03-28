---
layout: app

permalink: /Electron_Xiami/
description: Xiami Electron desktop application

icons:
  - Electron_Xiami/icons/128x128/electron-xiami.png

screenshots:
  - Electron_Xiami/screenshot.png

authors:
  - name: eNkru
    url: https://github.com/eNkru

links:
  - type: GitHub
    url: eNkru/electron-xiami
  - type: Download
    url: https://github.com/eNkru/electron-xiami/releases

desktop:
  Desktop Entry:
    Name: Xiami Music
    Comment: Xiami Electron desktop application
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: electron-xiami
    StartupWMClass: xiami music
    X-AppImage-Version: 1.5.2
    Categories: AudioVideo
    X-AppImage-BuildId: 1FPtS7xHR243cabsyFcOunSZkCI
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Xiami Electron desktop application
  main: src/main.js
  repository: https://github.com/eNkru/electron-xiami
  author: Howard Ju <howard.ju@outlook.com>
  license: MIT
  dependencies:
    dbus-native: "^0.2.5"
    download: "^6.2.5"
    electron-json-storage: "^4.0.2"
    electron-settings: "^3.1.1"
    electron-updater: "^3.0.3"
    fs-extra: "^5.0.0"
    hh-mm-ss: "^1.2.0"
    lyrics.js: "^0.3.5"
---
