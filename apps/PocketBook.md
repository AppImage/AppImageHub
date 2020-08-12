---
layout: app

permalink: /PocketBook/
description: An electron-vue project
license: MIT

icons:
  - PocketBook/icons/256x256/pocketbook.png

screenshots:
  - PocketBook/screenshot.png

authors:
  - name: hilanmiao
    url: https://github.com/hilanmiao

links:
  - type: GitHub
    url: hilanmiao/LanMiaoDesktop
  - type: Download
    url: https://github.com/hilanmiao/LanMiaoDesktop/releases

desktop:
  Desktop Entry:
    Name: PocketBook
    Comment: An electron-vue project
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: pocketbook
    StartupWMClass: PocketBook
    X-AppImage-Version: 0.0.2.25
    Categories: Utility
    X-AppImage-BuildId: 1KwWDBMqZjggQ5wIVTrX3kVdwwK
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: An electron-vue project
  license: MIT
  main: "./dist/electron/main.js"
  dependencies:
    axios: "^0.18.0"
    electron-updater: "^4.0.6"
    material-design-icons-iconfont: "^4.0.5"
    vue: "^2.6.10"
    vue-electron: "^1.0.6"
    vue-router: "^3.0.3"
    vuetify: "^1.5.11"
    vuex: "^3.1.0"
    vuex-electron: "^1.0.3"
    winreg: "^1.2.4"
---
