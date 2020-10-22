---
layout: app

permalink: /Passerine/
description: Product Hunt desktop app

icons:
  - Passerine/icons/128x128/passerine.png

screenshots:
  - Passerine/screenshot.png

authors:
  - name: aviary-apps
    url: https://github.com/aviary-apps

links:
  - type: GitHub
    url: aviary-apps/Passerine
  - type: Download
    url: https://github.com/aviary-apps/Passerine/releases

desktop:
  Desktop Entry:
    Name: passerine
    Comment: Product Hunt desktop app
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: passerine
    X-AppImage-Version: 1.0.1
    X-AppImage-BuildId: 84bb7f50-1f82-11a8-1dad-7ba9b008b18f
    Categories: Chat
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  license: MIT
  repository: github.com/aviary-apps/Passerine
  author:
    name: Aviary Apps
    email: thabeatsz@gmail.com
    url: gauthamzz.com
  dependencies:
    electron-context-menu: "^0.9.1"
    electron-debug: "^1.4.0"
    electron-dl: "^1.0.0"
    electron-is-dev: "^0.3.0"
    electron-localshortcut: "^2.0.0"
    electron-log: "^2.0.2"
    electron-store: "^1.1.0"
    electron-updater: "^2.18.2"
    element-ready: "^2.2.0"
    facebook-locales: "^1.0.464"
---
