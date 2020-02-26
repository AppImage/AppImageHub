---
layout: app

permalink: /uLaunch-Previewer/
description: uLaunch Previewer

icons:
  - uLaunch-Previewer/icons/128x128/ulaunch-previewer.png

screenshots:
  - uLaunch-Previewer/screenshot.png

authors:
  - name: IcosaSwitch
    url: https://github.com/IcosaSwitch

links:
  - type: GitHub
    url: IcosaSwitch/uLaunch-Previewer
  - type: Download
    url: https://github.com/IcosaSwitch/uLaunch-Previewer/releases

desktop:
  Desktop Entry:
    Name: uLaunch Previewer
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: ulaunch-previewer
    StartupWMClass: uLaunch Previewer
    X-AppImage-Version: 0.1.0
    Comment: uLaunch Previewer
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: index.js
  homepage: https://github.com/IcosaSwitch/uLaunch-Previewer#readme
  author: Pharuxtan
  dependencies:
    ejs: "^2.6.1"
    ejs-electron: "^2.0.3"
    fs: 0.0.1-security
    howler: "^2.1.2"
    html2canvas: "^1.0.0-rc.5"
    https-proxy-agent: "^3.0.1"
    jquery: "^3.4.1"
    node-fetch: "^2.6.0"
    path: "^0.12.7"
    platform-folders: "^0.4.1"
    url: "^0.11.0"
---
