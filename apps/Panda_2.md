---
layout: app

permalink: /Panda_2/
description: Game Development Platform

icons:
  - Panda_2/icons/128x128/panda2-trial.png

screenshots:
  - Panda_2/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: Panda 2
    Comment: Game Development Platform
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: panda2-trial
    X-AppImage-Version: 1.6.0
    X-AppImage-BuildId: bfced6b0-ba4a-11a8-0ebc-559b7997de0b
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Game Development Platform
  author: Eemeli Kelokorpi
  homepage: https://www.panda2.io
  license: Copyright © 2018 Eemeli Kelokorpi
  main: main.js
  dependencies:
    adbkit: "^2.11.0"
    archiver: "^2.1.0"
    bluebird: "^3.5.1"
    connect-inject: "^0.4.0"
    cordova: ">6.0.0"
    cors: "^2.8.4"
    electron-log: "^2.2.9"
    electron-window-state: "^4.1.1"
    express: "^4.14.1"
    javascript-obfuscator: "^0.16.0"
    node-watch: "^0.5.7"
    opener: "^1.4.3"
    panda-toolkit: file:../../panda-toolkit
    phonegap-build-api: "^0.4.0"
    sanitize-filename: "^1.6.1"
    shelljs: "^0.7.6"
    socket.io: "^1.7.2"
  trial: true
---
