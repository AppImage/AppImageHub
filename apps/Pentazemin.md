---
layout: app

permalink: /Pentazemin/
description: The Pomodoro technique based task management app. Helps your aiming for to do.

screenshots:
  - Pentazemin/screenshot.png

authors:
  - name: AquiTCD
    url: https://github.com/AquiTCD

links:
  - type: GitHub
    url: AquiTCD/Pentazemin
  - type: Install
    url: https://github.com/AquiTCD/Pentazemin/releases

desktop:
  Desktop Entry:
    Name: Pentazemin
    Comment: The Pomodoro technique based task management app. Helps your aiming for
      to do.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: pentazemin
    X-AppImage-Version: 0.1.1.18
    X-AppImage-BuildId: 3a744e40-ddfb-11a7-0798-df9c47a6565c
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: The Pomodoro technique based task management app. Helps your aiming for
    to do.
  license: MIT
  main: "./dist/electron/main.js"
  lint-staged:
    "*.{js}":
    - prettier-eslint --write
    - eslint
    - git add
  dependencies:
    axios: "^0.16.1"
    buefy: "^0.5.1"
    d3: "^4.10.2"
    font-awesome: "^4.7.0"
    lodash: "^4.17.4"
    menubar: "^5.2.3"
    moment: "^2.18.1"
    moment-duration-format: "^1.3.0"
    nedb: "^1.8.0"
    uuid: "^3.1.0"
    vue: "^2.3.3"
    vue-electron: "^1.0.6"
    vue-multiselect: "^2.0.2"
    vue-router: "^2.5.3"
    vuedraggable: "^2.14.1"
    vuex: "^2.3.1"
---
