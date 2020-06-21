---
layout: app

permalink: /Hackaru/
description: An electron-vue project
license: MIT

icons:
  - Hackaru/icons/128x128/hackaru.png

screenshots:
  - Hackaru/screenshot.png

authors:
  - name: ktmouk
    url: https://github.com/ktmouk

links:
  - type: GitHub
    url: ktmouk/hackaru-desktop
  - type: Download
    url: https://github.com/ktmouk/hackaru-desktop/releases

desktop:
  Desktop Entry:
    Name: Hackaru
    Comment: An electron-vue project
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: hackaru
    StartupWMClass: Hackaru
    X-AppImage-Version: 0.1.0
    Categories: Utility
    X-AppImage-BuildId: 1JffFmv2x5JKrcFNt2bIxgSbIwY
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: An electron-vue project
  license: 
  main: "./dist/electron/main.js"
  dependencies:
    axios: "^0.18.0"
    camelcase-keys: "^5.0.0"
    date-fns: "^1.30.1"
    electron-promise-ipc: "^1.0.0"
    electron-store: "^2.0.0"
    feather-icons: "^4.10.0"
    hh-mm-ss: "^1.2.0"
    keytar: "^4.3.0"
    lodash.get: "^4.4.2"
    lodash.union: "^4.6.0"
    lodash.uniq: "^4.5.0"
    node-notifier: "^5.3.0"
    normalize.css: "^8.0.1"
    normalizr: "^3.3.0"
    ps-list: "^6.0.0"
    query-string: "^6.2.0"
    snakecase-keys: "^2.1.0"
    uniqid: "^5.0.3"
    updeep: "^1.1.0"
    vue: "^2.5.16"
    vue-electron: "^1.0.6"
    vue-i18n: "^8.7.0"
    vue-multiselect: "^2.1.3"
    vue-notification: "^1.3.14"
    vue-router: "^3.0.1"
    vue-timers: "^1.10.0"
    vue2-animate: "^2.1.0"
    vuex: "^3.0.1"
    vuex-electron: "^1.0.0"
    vuex-persistedstate: "^2.5.4"
---
