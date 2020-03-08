---
layout: app

permalink: /us-connector/
description: untermStrich Connector

icons:
  - us-connector/icons/128x128/us-connector.png

screenshots:
  - us-connector/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: untermStrich Connector
    Comment: untermStrich Connector
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: us-connector
    StartupWMClass: untermStrich Connector
    X-AppImage-Version: 2.0.22
    Categories: Utility
    X-AppImage-BuildId: 1Cvi59x8UH5UcLcI6SC0KCxt3aD
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: untermStrich Connector
  author: Christian Koller
  private: true
  dependencies:
    "@panter/vue-i18next": "^0.13.0"
    electron-updater: "^3.1.2"
    i18next: "^11.9.0"
    i18next-electron-language-detector: "^0.0.10"
    i18next-resource-store-loader: "^0.1.2"
    source-map-support: "^0.5.9"
  resolutions:
    upath: "^1.0.5"
  electronWebpack:
    title: untermStrich Connector
  main: main.js
---
