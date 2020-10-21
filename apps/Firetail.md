---
layout: app

permalink: /Firetail/
description: Audio Player

icons:
  - Firetail/icons/128x128/firetail.png

screenshots:
  - Firetail/screenshot.png

authors:
  - name: projsh
    url: https://github.com/projsh

links:
  - type: GitHub
    url: projsh/firetail
  - type: Download
    url: https://github.com/projsh/firetail/releases

desktop:
  Desktop Entry:
    Name: Firetail
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: firetail
    StartupWMClass: Firetail
    X-AppImage-Version: 0.4.0.121
    Comment: Audio Player
    Categories: AudioVideo
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  author:
    name: projsh_
    email: projshdev@gmail.com
  repository: https://github.com/projsh/firetail.git
  main: main.js
  dependencies:
    discord-rpc: "^3.0.1"
    electron-settings: "^3.2.0"
    express: "^4.17.1"
    fs-extra: "^8.1.0"
    jsmediatags: "^3.8.1"
    markdown-it: "^9.0.0"
    tmp: "^0.0.33"
  optionalDependencies:
    mpris-service: "^2.1.0"
    "@nodert-win10/windows.foundation": "^0.2.96"
    "@nodert-win10/windows.media": "^0.2.96"
    "@nodert-win10/windows.media.playback": "^0.2.96"
    "@nodert-win10/windows.storage.streams": "^0.2.96"
---
