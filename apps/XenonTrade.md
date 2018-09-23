---
layout: app

permalink: /XenonTrade/
description: Path of Exile trading app for price checking and whisper management

icons:
  - XenonTrade/icons/128x128/xenontrade.png

screenshots:
  - XenonTrade/screenshot.png

authors:
  - name: klayveR
    url: https://github.com/klayveR

links:
  - type: GitHub
    url: klayveR/xenontrade
  - type: Download
    url: https://github.com/klayveR/xenontrade/releases

desktop:
  Desktop Entry:
    Name: XenonTrade
    Comment: Path of Exile trading app for price checking and whisper management
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: xenontrade
    StartupWMClass: XenonTrade
    X-AppImage-Version: 0.3.8
    Categories: Game
    X-AppImage-BuildId: 1AWH8AjaxoTsStgiCiE4zWXJnB4
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: src/main.js
  homepage: https://github.com/klayveR/xenontrade#readme
  bugs:
    url: https://github.com/klayveR/xenontrade/issues
  author:
    name: Tobias Hoffmann
    email: tobiashoffmann7@gmail.com
    url: http://klayver.de
  repository:
    type: git
    url: https://github.com/klayveR/xenontrade.git
  license: MIT
  dependencies:
    active-win: "^3.0.0"
    child-process-es6-promise: "^1.2.0"
    clipboardy: github:klayveR/clipboardy
    electron-is-dev: "^0.3.0"
    electron-log: "^2.2.17"
    electron-store: "^2.0.0"
    electron-updater: "^3.1.2"
    ffi: "^2.2.0"
    iohook: "^0.2.0"
    jquery: "^3.3.1"
    js-base64: "^2.4.9"
    poe-ninja-api-manager: "^0.7.0"
    promise-fs: "^1.3.0"
    request-promise-native: "^1.0.5"
    underscore: "^1.9.1"
    x11: "^2.3.0"
    x11-prop: "^0.4.3"
  cmake-js:
    runtime: electron
    runtimeVersion: 2.0.8
  iohook:
    targets:
    - node-59
    - electron-57
    platforms:
    - win32
    - linux
    arches:
    - x64
    - ia32
---
