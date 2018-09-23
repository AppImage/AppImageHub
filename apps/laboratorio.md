---
layout: app

permalink: /laboratorio/
description: An electron-vue project
license: MIT

icons:
  - laboratorio/icons/256x256/laboratorio.png

screenshots:
  - laboratorio/screenshot.png

authors:
  - name: marianorodriguez
    url: https://github.com/marianorodriguez

links:
  - type: GitHub
    url: marianorodriguez/laboratorio
  - type: Download
    url: https://github.com/marianorodriguez/laboratorio/releases

desktop:
  Desktop Entry:
    Name: laboratorio
    Comment: An electron-vue project
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: laboratorio
    StartupWMClass: laboratorio
    X-AppImage-Version: 0.0.4
    Categories: Utility
    X-AppImage-BuildId: 1AJCdg66SBTlOv8NZZ01HCkQl97
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
  repository: https://github.com/marianorodriguez/laboratorio
  dependencies:
    axios: "^0.18.0"
    body-parser: "^1.18.3"
    electron-log: "^2.2.17"
    electron-updater: "^3.1.2"
    express: "^4.16.3"
    vue: "^2.5.16"
    vue-electron: "^1.0.6"
    vue-router: "^3.0.1"
    vuex: "^3.0.1"
---
