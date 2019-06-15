---
layout: app

permalink: /Network_Canvas/
description: Simplifying complex network data collection.
license: GPL-3.0

icons:
  - Network_Canvas/icons/128x128/network-canvas.png

screenshots:
  - Network_Canvas/screenshot.png

authors:
  - name: codaco
    url: https://github.com/codaco

links:
  - type: GitHub
    url: codaco/Network-Canvas
  - type: Download
    url: https://github.com/codaco/Network-Canvas/releases

desktop:
  Desktop Entry:
    Name: Network Canvas
    Comment: Simplifying complex network data collection.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: network-canvas
    StartupWMClass: Network Canvas
    X-AppImage-Version: 4.0.0
    Categories: Education
    X-AppImage-BuildId: 1MadOSgxiwuWPFiPWhEJLQDCrei
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  description: Simplifying complex network data collection.
  author: Complex Data Collective
  private: true
  homepage: "."
  main: electron-starter.js
  dependencies:
    electron-log: "^2.2.17"
    electron-updater: "^3.2.3"
    mdns: "^2.4.0"
    secure-comms-api: git+https://github.com/codaco/secure-comms-api.git
---
