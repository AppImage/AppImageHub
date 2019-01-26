---
layout: app

permalink: /podpup/
description: An electron-vue project

icons:
  - podpup/icons/256x256/podpup.png

screenshots:
  - podpup/screenshot.png

authors:
  - name: erikssource
    url: https://github.com/erikssource

links:
  - type: GitHub
    url: erikssource/podpup
  - type: Download
    url: https://github.com/erikssource/podpup/releases

desktop:
  Desktop Entry:
    Name: podpup
    Comment: An electron-vue project
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: podpup
    StartupWMClass: podpup
    X-AppImage-Version: 0.3.0
    Categories: AudioVideo
    X-AppImage-BuildId: 1FCD58cPBrgxwdiD6zQGD9Q7YI4
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: An electron-vue project
  license: GPL-3.0
  main: "./dist/electron/main.js"
  repository:
    type: git
    url: https://github.com/erikssource/podpup
  jest:
    testEnvironment: node
  dependencies:
    "@saeris/vue-spinners": "^1.0.8"
    better-sqlite3: "^5.2.1"
    bootstrap-vue: "^2.0.0-rc.11"
    emotion: 9.2.6
    event-stream: 3.3.4
    file-url: "^2.0.2"
    filenamify: "^2.1.0"
    howler: "^2.1.1"
    install: "^0.12.2"
    itunes-podcasts: "^1.0.1"
    jquery: "^3.3.1"
    node-podcast-parser: "^2.3.0"
    printf: "^0.5.1"
    request: "^2.88.0"
    request-progress: "^3.0.0"
    validator: "^10.10.0"
    vue: "^2.5.21"
    vue-electron: "^1.0.6"
    vue-emotion: "^0.4.2"
    vue-fixed-header: "^2.0.2"
    vue-resize-split-pane: "^0.1.3"
    vue-sanitize: "^0.2.0"
    vue-slider-component: "^2.8.3"
    vue-toasted: "^1.1.26"
    vuex: "^3.0.1"
  optionalDependencies:
    dbus-native: "^0.4.0"
---
