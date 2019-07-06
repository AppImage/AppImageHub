---
layout: app

permalink: /Batch_Explorer/
description: Batch Explorer is a tool to manage your Azure Batch accounts

icons:
  - Batch_Explorer/icons/128x128/batch-explorer.png

screenshots:
  - Batch_Explorer/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: BatchExplorer
    Comment: Batch Explorer is a tool to manage your Azure Batch accounts
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: batch-explorer
    StartupWMClass: BatchExplorer
    X-AppImage-Version: 0.19.2-stable.231.231
    MimeType: x-scheme-handler/ms-batchlabs
    Categories: Development
    X-AppImage-BuildId: 1Fx3FzaBBXu7fes23QrZym4z7Wn
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  - src/app/environment.ts
  - "*.scss"
  productName: Batch Explorer
  description: Batch Explorer is a tool to manage your Azure Batch accounts
  repository:
    type: git
    url: https://github.com/Azure/BatchExplorer
  author:
    name: Microsoft Corporation
    email: tiguerin@microsoft.com
  version: 0.19.2-stable.231
  main: build/client/main.prod.js
  license: MIT
  engines:
    node: ">=6.0.0"
  dependencies:
    "@angular/animations": "^7.0.1"
    "@angular/cdk": "^7.0.2"
    "@angular/common": "^7.0.1"
    "@angular/compiler": "^7.1.2"
    "@angular/compiler-cli": "^7.1.2"
    "@angular/core": "^7.1.2"
    "@angular/forms": "^7.1.2"
    "@angular/http": "^7.1.2"
    "@angular/material": "^7.1.1"
    "@angular/platform-browser": "^7.1.2"
    "@angular/platform-browser-dynamic": "^7.1.2"
    "@angular/platform-server": "^7.1.2"
    "@angular/router": "^7.1.2"
    "@azure/storage-blob": "^10.1.0-preview"
    "@types/keytar": "^4.0.1"
    applicationinsights: "^1.0.7"
    azure-storage: "^2.10.2"
    bunyan: "^1.8.12"
    chart.js: "^2.7.3"
    chokidar: "^2.0.4"
    commander: "^2.19.0"
    d3: "^5.7.0"
    decode-uri-component: "^0.2.0"
    download: "^7.1.0"
    electron-updater: "^3.2.3"
    element-resize-detector: "^1.2.0"
    extract-zip: "^1.6.7"
    focus-visible: "^4.1.5"
    font-awesome: "^4.7.0"
    get-proxy-settings: "^0.1.11"
    glob: "^7.1.3"
    hammerjs: "^2.0.8"
    https-proxy-agent: "^2.2.1"
    immutable: "^3.8.2"
    inflection: "^1.12.0"
    js-yaml: "^3.12.0"
    jschardet: "^1.6.0"
    keytar: "^4.3.0"
    load-json-file: "^5.1.0"
    mkdirp: "^0.5.1"
    moment: "^2.22.2"
    moment-duration-format: "^2.2.2"
    monaco-editor: "^0.15.6"
    mousetrap: "^1.6.2"
    node-forge: "^0.7.6"
    patternomaly: "^1.3.2"
    reflect-metadata: "^0.1.12"
    rxjs: "^6.3.3"
    strip-json-comments: "^2.0.1"
    tinycolor2: "^1.4.1"
    write-file-webpack-plugin: "^4.5.0"
    xml2js: "^0.4.19"
    zone.js: 0.8.26
---
