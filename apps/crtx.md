---
layout: app

permalink: /crtx/
description: Cortex Desktop App

icons:
  - crtx/icons/512x512/crtx.png

screenshots:
  - crtx/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: Cortex
    Comment: Cortex Desktop App
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: crtx
    StartupWMClass: Cortex
    X-AppImage-Version: 0.1.9-beta
    Categories: Utility
    X-AppImage-BuildId: 1E1eii6eBeiBcx6w7AFeYv3D19o
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  dependencies:
    "@fortawesome/fontawesome-svg-core": "^1.2.8"
    "@fortawesome/free-solid-svg-icons": "^5.5.0"
    "@fortawesome/vue-fontawesome": "^0.1.2"
    "@sentry/browser": "^4.3.0"
    "@sentry/node": "^4.3.0"
    electron-updater: "^4.0.5"
    firebase: "^5.5.8"
    getstream: "^4.0.2"
    iohook: "^0.2.0"
    moment: "^2.22.2"
    nedb: "^1.8.0"
    ps-list: "^6.0.0"
    simpleheat: "^0.4.0"
    systeminformation: "^3.45.10"
    vue: "^2.5.17"
    vue-electron: "^1.0.6"
    vue-i18n: "^8.2.1"
    vue-router: "^3.0.1"
    vue-ua: "^1.5.0"
    vuetrend: "^0.3.2"
    vuex: "^3.0.1"
  description: Cortex Desktop App
  license: UNLICENSED
  homepage: https://crtx.gg
  iohook:
    targets:
    - node-59
    - electron-64
    platforms:
    - win32
    - darwin
    - linux
    arches:
    - x64
    - ia32
  author:
    name: Cortex
    email: hello@crtx.gg
    url: https://crtx.gg
  main: background.js
  repository:
    type: git
    url: git+https://gitlab.com/crtxgg/desktop-app.git
---
