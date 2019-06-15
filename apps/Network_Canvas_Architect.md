---
layout: app

permalink: /Network_Canvas_Architect/
description: A tool for creating Network Canvas interviews.
license: GPL-3.0

icons:
  - Network_Canvas_Architect/icons/128x128/network-canvas-architect.png

screenshots:
  - Network_Canvas_Architect/screenshot.png

authors:
  - name: codaco
    url: https://github.com/codaco

links:
  - type: GitHub
    url: codaco/Architect
  - type: Download
    url: https://github.com/codaco/Architect/releases

desktop:
  Desktop Entry:
    Name: Network Canvas Architect
    Comment: A tool for creating Network Canvas interviews.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: network-canvas-architect
    StartupWMClass: Network Canvas Architect
    X-AppImage-Version: 4.0.0
    Categories: Education
    X-AppImage-BuildId: 1MatXwC61FBBMEvOYuIJMOiNGDM
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  description: A tool for creating Network Canvas interviews.
  author: Complex Data Collective
  private: true
  engines:
    node: 8.16.0
    npm: 6.4.1
  homepage: "."
  main: electron-starter.js
  dependencies:
    electron-log: "^2.2.7"
    electron-updater: "^3.2.3"
  browser:
    canvas: false
    jsdom: false
---
