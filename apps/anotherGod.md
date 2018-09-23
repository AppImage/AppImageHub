---
layout: app

permalink: /anotherGod/
description: Another Gmail on the Dock
license: GPL-3.0

icons:
  - anotherGod/icons/128x128/anothergod.png

screenshots:
  - anotherGod/screenshot.png

authors:
  - name: tosolini
    url: https://github.com/tosolini

links:
  - type: GitHub
    url: tosolini/anotherGod
  - type: Download
    url: https://github.com/tosolini/anotherGod/releases

desktop:
  Desktop Entry:
    Name: anotherGod
    Comment: Another Gmail on the Dock
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: anothergod
    StartupWMClass: anotherGod
    X-AppImage-Version: 0.6.0
    Categories: Network
    X-AppImage-BuildId: 1AWXhMgLme9CBzPCco8a4SCIlDn
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  description: Another Gmail on the Dock
  author:
    name: Walter Tosolini
    email: software@tosolini.info
    url: https://tosolini.info
  license: GPL-3.0
  repository:
    type: git
    url: https://github.com/tosolini/anotherGod.git
  bugs:
    url: https://github.com/tosolini/anotherGod/issues
  main: main.js
  dependencies:
    ajv: "^6.5.3"
    ajv-keywords: "^3.2.0"
    auto-launch: "^5.0.5"
    electron-is-dev: "^0.3.0"
    electron-updater: "^3.1.2"
    electron-window-state: "^4.1.1"
    jquery: "^3.3.1"
---
