---
layout: app

permalink: /SwapperdD_Desktop/
description: The native Desktop interface for SwapperD
license: GPL-3.0

icons:
  - SwapperdD_Desktop/icons/512x512/swapperd-desktop.png

screenshots:
  - SwapperdD_Desktop/screenshot.png

authors:
  - name: renproject
    url: https://github.com/renproject

links:
  - type: GitHub
    url: renproject/swapperd-desktop
  - type: Download
    url: https://github.com/renproject/swapperd-desktop/releases

desktop:
  Desktop Entry:
    Name: SwapperD Desktop
    Comment: The native Desktop interface for SwapperD
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: swapperd-desktop
    StartupWMClass: SwapperD Desktop
    X-AppImage-Version: 1.0.0-beta.2
    Categories: Utility
    X-AppImage-BuildId: 1HhihmOxPXr08rEQfhNlrOjx3Hr
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  author: Ren
  license: MIT
  dependencies:
    "@types/rc-progress": "^2.2.1"
    auto-launch: "^5.0.5"
    axios: "^0.18.0"
    bcryptjs: "^2.4.3"
    bignumber.js: "^8.0.2"
    body-parser: "^1.18.3"
    electron-store: "^2.0.0"
    electron-updater: "^4.0.6"
    express: "^4.16.4"
    immutable: "^4.0.0-rc.12"
    menubar: "^5.2.3"
    moment: "^2.24.0"
    rc-progress: "^2.3.0"
    react: "^16.7.0"
    react-copy-to-clipboard: "^5.0.1"
    react-dom: "^16.7.0"
    react-keybinding-component: "^1.0.0"
    source-map-support: "^0.5.10"
    sqlite3: "^4.0.6"
    unstated: "^2.1.1"
  main: main.js
---
