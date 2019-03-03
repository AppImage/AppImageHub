---
layout: app

permalink: /shikme-electron/
description: Electron app for Shikme
license: MIT

icons:
  - shikme-electron/icons/128x128/shikme-electron.png

screenshots:
  - shikme-electron/screenshot.png

authors:
  - name: yegorgunko
    url: https://github.com/yegorgunko

links:
  - type: GitHub
    url: yegorgunko/shikme-electron
  - type: Download
    url: https://github.com/yegorgunko/shikme-electron/releases

desktop:
  Desktop Entry:
    Name: Shikme
    Comment: Electron app for Shikme
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: shikme-electron
    StartupWMClass: Shikme
    X-AppImage-Version: 1.0.8
    Categories: Network
    X-AppImage-BuildId: 1HrgH5XrbPMc5W1CUlPhR4edZuR
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  main: src/app.js
  homepage: https://shikme.ru
  repository:
    type: git
    url: https://github.com/yegorgunko/shikme-electron.git
  author: Yegor Gunko
  license: MIT
  dependencies:
    electron-context-menu: "^0.11.0"
    electron-is-dev: "^1.0.1"
    electron-store: "^2.0.0"
    electron-updater: "^4.0.6"
---
