---
layout: app

permalink: /IIROSE/
description: IIROSE
license: Apache-2.0

icons:
  - IIROSE/icons/128x128/iirose.png

screenshots:
  - IIROSE/screenshot.png

authors:
  - name: iirose-tools
    url: https://github.com/iirose-tools

links:
  - type: GitHub
    url: iirose-tools/electron-iirose
  - type: Download
    url: https://github.com/iirose-tools/electron-iirose/releases

desktop:
  Desktop Entry:
    Name: Electron-IIROSE
    Comment: IIROSE
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: iirose
    StartupWMClass: Electron-IIROSE
    X-AppImage-Version: 0.0.3
    Categories: Utility
    X-AppImage-BuildId: 1It831weFWoJOuJUuI6hTsnjeBc
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: Apache-2.0

electron:
  main: main.js
  author: Theresa
  dependencies:
    request: "^2.88.0"
---
