---
layout: app

permalink: /Gong/
description: XMPP Client
license: Apache-2.0

icons:
  - Gong/icons/128x128/gong.png

screenshots:
  - Gong/screenshot.png

authors:
  - name: gongchat
    url: https://github.com/gongchat

links:
  - type: GitHub
    url: gongchat/gong
  - type: Download
    url: https://github.com/gongchat/gong/releases

desktop:
  Desktop Entry:
    Name: Gong
    Comment: XMPP Client
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: gong
    StartupWMClass: Gong
    X-AppImage-Version: 0.1.2.56
    Categories: Utility
    X-AppImage-BuildId: 1ImRZH3vuVfHtHqW6gqn5kth9qP
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: Apache-2.0

electron:
  author: Gong <gongxmpp@gmail.com>
  main: build/electron.js
  homepage: "./"
  engines:
    node: 10.13.0
  dependencies:
    "@material-ui/core": 3.9.2
    "@material-ui/icons": 3.0.1
    "@material-ui/lab": 3.0.0-alpha.30
    "@techempower/react-governor": 0.1.1
    crypto-js: 3.1.9-1
    electron-devtools-installer: 2.2.4
    electron-is-dev: 1.0.1
    electron-log: "^3.0.1"
    electron-store: 2.0.0
    electron-updater: 4.0.6
    keytar: 4.3.0
    markdown-it: 8.4.2
    markdown-it-emoji: 1.4.0
    moment: 2.22.2
    notistack: 0.4.2
    react: 16.8.1
    react-dev-utils: 6.1.1
    react-dom: 16.6.1
    react-material-ui-form-validator: 2.0.3
    react-player: 1.8.0
    react-redux: 5.0.7
    react-router-dom: 4.3.1
    redux: 4.0.0
    redux-devtools-extension: 2.13.7
    redux-thunk: 2.3.0
    sanitize-html: 1.19.1
    webfontloader: 1.6.28
    xmpp.js: 0.7.0
---
