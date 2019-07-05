---
layout: app

permalink: /laravel-kit/
description: Easy Laravel application management

icons:
  - laravel-kit/icons/128x128/laravel-kit.png

screenshots:
  - laravel-kit/screenshot.png

authors:
  - name: tarequemdhanif
    url: https://github.com/tarequemdhanif

links:
  - type: GitHub
    url: tarequemdhanif/laravel-kit
  - type: Download
    url: https://github.com/tarequemdhanif/laravel-kit/releases

desktop:
  Desktop Entry:
    Name: Laravel Kit
    Comment: Easy Laravel application management
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: laravel-kit
    X-AppImage-Version: 1.2.2.63
    X-AppImage-BuildId: f6e81160-2095-11a8-3775-0d1679dc897a
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: main.js
  author: Tareque Md Hanif <tarequemd.hanif@yahoo.com>
  license: MIT
  homepage: https://github.com/tarequemdhanif/laravel-kit
  url: https://github.com/tarequemdhanif/laravel-kit/issues
  repository:
    type: git
    url: https://github.com/tarequemdhanif/laravel-kit.git
  dependencies:
    electron-is-dev: "^0.3.0"
    electron-settings: "^3.1.4"
    electron-updater: "^2.18.2"
    electron-window-state: "^4.1.1"
    extract-zip: "^1.6.6"
    is-online: "^7.0.0"
    request: "^2.83.0"
    tree-kill: "^1.2.0"
---
