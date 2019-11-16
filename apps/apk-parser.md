---
layout: app

permalink: /apk-parser/
description: An electron-vue project

icons:
  - apk-parser/icons/256x256/apk-parser.png

screenshots:
  - apk-parser/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: apk-parser
    Comment: An electron-vue project
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: apk-parser
    X-AppImage-Version: 1.0.0
    X-AppImage-BuildId: 6c8e6a90-7a82-11a8-1232-81044839d058
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: An electron-vue project
  license: GPL
  main: "./dist/electron/main.js"
  dependencies:
    md5-file: "^4.0.0"
    vue: "^2.3.3"
    vue-electron: "^1.0.6"
---
