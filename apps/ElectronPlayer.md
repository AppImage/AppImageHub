---
layout: app

permalink: /ElectronPlayer/
description: A Desktop App For Netflix Wirtten Using Electron.
license: MIT

icons:
  - ElectronPlayer/icons/128x128/netflix.png

screenshots:
  - ElectronPlayer/screenshot.png

authors:
  - name: oscartbeaumont
    url: https://github.com/oscartbeaumont

links:
  - type: GitHub
    url: oscartbeaumont/ElectronPlayer
  - type: Download
    url: https://github.com/oscartbeaumont/ElectronPlayer/releases

desktop:
  Desktop Entry:
    Name: Netflix
    Comment: A Desktop App For Netflix Wirtten Using Electron.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: netflix
    X-AppImage-Version: 1.0.0.39
    X-AppImage-BuildId: 72a7f690-84fe-11a8-1ef8-bb6a7a1b24b9
    Categories: Video
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  version: 1.0.0
  license: MIT
  dependencies:
    electron-widevinecdm: "^7.0.0"
    source-map-support: "^0.5.5"
  resolutions:
    webpack-sources: 1.0.1
  main: main.js
---
