---
layout: app

permalink: /Network_Canvas_Server/
description: A tool for storing, analyzing, and exporting Network Canvas interview data.
license: GPL-3.0

icons:
  - Network_Canvas_Server/icons/128x128/network-canvas-server.png

screenshots:
  - Network_Canvas_Server/screenshot.png

authors:
  - name: codaco
    url: https://github.com/codaco

links:
  - type: GitHub
    url: codaco/Server
  - type: Download
    url: https://github.com/codaco/Server/releases

desktop:
  Desktop Entry:
    Name: Network Canvas Server
    Comment: A tool for storing, analyzing, and exporting Network Canvas interview data.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: network-canvas-server
    StartupWMClass: Network Canvas Server
    X-AppImage-Version: 4.0.0
    Categories: Education
    X-AppImage-BuildId: 1MadOwplwYSuBs6MR9nfr6ONFbB
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  description: A tool for storing, analyzing, and exporting Network Canvas interview
    data.
  private: true
  author: Complex Data Collective
  engines:
    node: 8.16.0
    npm: 6.4.1
  dependencies:
    archiver: "^2.1.1"
    big-integer: "^1.6.43"
    detect-port: "^1.2.3"
    electron-log: "^2.2.16"
    electron-updater: "^3.2.3"
    jszip: "^3.1.5"
    libsodium-wrappers: "^0.7.3"
    lodash: "^4.17.11"
    mdns: "^2.4.0"
    nedb: "^1.8.0"
    prop-types: "^15.6.2"
    restify: "^7.2.1"
    restify-cors-middleware: "^1.1.1"
    selfsigned: "^1.10.3"
    uuid: "^3.3.2"
    xmldom: "^0.1.27"
  main: "./index.js"
---
