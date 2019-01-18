---
layout: app

permalink: /FTALK/
description: Chat FTALK

icons:
  - FTALK/icons/1024x1024/ftalk-electron.png

screenshots:
  - FTALK/screenshot.png

authors:
  - name: giovanni-finer
    url: https://github.com/giovanni-finer

links:
  - type: GitHub
    url: giovanni-finer/ftalk-electron
  - type: Download
    url: https://github.com/giovanni-finer/ftalk-electron/releases

desktop:
  Desktop Entry:
    Name: FTALK
    Comment: Chat FTALK
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: ftalk-electron
    StartupWMClass: FTALK
    X-AppImage-Version: 1.2.1
    Categories: Utility
    X-AppImage-BuildId: 1FwCZEEogkAYf70CezCoCv2dTqq
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Chat FTALK
  main: index.js
  author: Giovanni Pucci <giobaer2011@live.com> (http://www.finer.com.br)
  license: ISC
  dependencies:
    auto-launch: 5.0.5
    electron-is-dev: "^1.0.1"
    electron-log: 2.2.17
    electron-updater: 4.0.6
    electron-windows-badge: "^1.0.4"
    node-notifier: "^5.3.0"
    uuid: "^3.3.2"
---
