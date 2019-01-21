---
layout: app

permalink: /Sonist/
description: Music Player
license: MIT

icons:
  - Sonist/icons/128x128/sonist.png

screenshots:
  - Sonist/screenshot.png

authors:
  - name: yutent
    url: https://github.com/yutent

links:
  - type: GitHub
    url: yutent/sonist
  - type: Download
    url: https://github.com/yutent/sonist/releases

desktop:
  Desktop Entry:
    Name: Sonist
    Comment: Music Player
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: sonist
    StartupWMClass: Sonist
    X-AppImage-Version: 0.9.3
    Categories: AudioVideo
    X-AppImage-BuildId: 1G4lYx4G1JlqKwXJJsszkSuTgub
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  main: src/main.js
  author:
    name: yutent
    email: yutent@doui.cc
  homepage: https://yutent.me
  license: MIT
  dependencies:
    crypto.js: "^1.2.0"
    iofs: "^1.1.0"
---
