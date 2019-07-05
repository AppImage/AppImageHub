---
layout: app

permalink: /email-securely-app/
description: Unofficial desktop app for E2E encrypted email providers
license: MIT

icons:
  - email-securely-app/icons/128x128/email-securely-app.png

screenshots:
  - email-securely-app/screenshot.png

authors:
  - name: vladimiry
    url: https://github.com/vladimiry

links:
  - type: GitHub
    url: vladimiry/email-securely-app
  - type: Download
    url: https://github.com/vladimiry/email-securely-app/releases

desktop:
  Desktop Entry:
    Name: email-securely-app
    Comment: Unofficial desktop app for E2E encrypted email providers
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: email-securely-app
    StartupWMClass: email-securely-app
    X-AppImage-Version: 1.3.0.232
    Categories: Office
    X-AppImage-BuildId: 17wcPoPi3sDbM18JvECojz1BF3A
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  author: Vladimir Yakovlev <desktop-app@protonmail.ch>
  license: MIT
  homepage: https://github.com/vladimiry/email-securely-app
  repository: git@github.com:vladimiry/email-securely-app.git
  bugs:
    url: https://github.com/vladimiry/email-securely-app/issues
  main: "./app/electron-main.js"
  dependencies:
    about-window: 1.12.1
    class-transformer: 0.1.9
    class-transformer-validator: 0.5.0
    class-validator: 0.9.1
    compare-versions: 3.3.0
    electron-log: 2.2.16
    electron-rpc-api: 2.0.0
    electron-unhandled: 1.1.0
    electron-updater: 3.0.3
    fs-json-store: 2.0.2
    fs-json-store-encryption-adapter: 0.0.3
    jimp: 0.2.28
    keepasshttp-client: 2.2.6
    keytar: 4.2.1
    nano-sql: 1.7.3
    ramda: 0.25.0
    reflect-metadata: 0.1.12
    rolling-rate-limiter: 0.1.11
    rxjs: 6.2.2
    valid-url: 1.0.9
---
