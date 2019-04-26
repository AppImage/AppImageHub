---
layout: app

permalink: /Makerlog_Menubar/
description: A menubar app for Makerlog

icons:
  - Makerlog_Menubar/icons/512x512/makerlog-menubar.png

screenshots:
  - Makerlog_Menubar/screenshot.png

authors:
  - name: Booligoosh
    url: https://github.com/Booligoosh

links:
  - type: GitHub
    url: Booligoosh/makerlog-menubar
  - type: Download
    url: https://github.com/Booligoosh/makerlog-menubar/releases

desktop:
  Desktop Entry:
    Name: Makerlog Menubar
    Comment: A menubar app for Makerlog
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: makerlog-menubar
    StartupWMClass: Makerlog Menubar
    X-AppImage-Version: 1.0.7
    Categories: Office
    X-AppImage-BuildId: 1KOksZpaFJApWg972dAO9MlSKJd
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  author:
    name: Ethan
    email: me@ethan.link
  dependencies:
    dotenv: "^7.0.0"
    electron-json-storage: "^4.1.6"
    rws: 0.0.1
    yarn: "^1.15.2"
  main: main.js
---
