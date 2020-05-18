---
layout: app

permalink: /Audiation/
description: An open-source music player
license: GPL-3.0

icons:
  - Audiation/icons/1080x1080/audiation.png

screenshots:
  - Audiation/screenshot.png

authors:
  - name: projsh
    url: https://github.com/projsh

links:
  - type: GitHub
    url: projsh/audiation
  - type: Download
    url: https://github.com/projsh/audiation/releases

desktop:
  Desktop Entry:
    Name: Audiation
    Comment: An open-source music player
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: audiation
    StartupWMClass: Audiation
    X-AppImage-Version: 1.0.0
    Categories: Audio
    X-AppImage-BuildId: 1DF30t9bZDfdbCiZD4Wifmyy3eM
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  author:
    name: projsh
    email: thisisafakeemail@gmail.com
  main: main.js
  dependencies:
    jsmediatags: "^3.8.1"
  optionalDependencies:
    mpris-service: "^1.1.4"
---
