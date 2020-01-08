---
layout: app

permalink: /Sovren_Batch_Parser/
description: Sovren Batch Parser

icons:
  - Sovren_Batch_Parser/icons/128x128/sovren-batch-utility.png

screenshots:
  - Sovren_Batch_Parser/screenshot.png

authors:
  - name: sovren
    url: https://github.com/sovren

links:
  - type: GitHub
    url: sovren/batch-utility
  - type: Download
    url: https://github.com/sovren/batch-utility/releases

desktop:
  Desktop Entry:
    Name: Sovren Batch Parser
    Comment: Sovren Batch Parser
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: sovren-batch-utility
    X-AppImage-Version: 1.0.0
    X-AppImage-BuildId: 833bc480-5a17-11a8-29e1-a776add3a051
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  author: Sovren <support@sovren.com>
  version: 1.0.0
  license: MIT
  main: main.js
  private: true
  dependencies:
    "@angular/animations": "^6.0.1"
    "@angular/common": "^6.0.1"
    "@angular/compiler": "^6.0.1"
    "@angular/core": "^6.0.1"
    "@angular/forms": "^6.0.1"
    "@angular/http": "^6.0.1"
    "@angular/platform-browser": "^6.0.1"
    "@angular/platform-browser-dynamic": "^6.0.1"
    "@angular/platform-server": "^6.0.1"
    "@angular/router": "^6.0.1"
    "@clr/angular": "^0.11.17"
    "@clr/icons": "^0.11.17"
    "@clr/ui": "^0.11.17"
    "@webcomponents/custom-elements": "^1.1.1"
    bootstrap: "^4.1.1"
    core-js: "^2.5.6"
    electron-store: "^1.3.0"
    jquery: "^3.3.1"
    moment: "^2.22.1"
    ngx-electron: "^1.0.4"
    popper.js: "^1.14.3"
    rxjs: "^6.1.0"
    rxjs-compat: "^6.1.0"
    winston: "^2.4.2"
    zone.js: "^0.8.19"
---
