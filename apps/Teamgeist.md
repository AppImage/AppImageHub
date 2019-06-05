---
layout: app

permalink: /Teamgeist/
description: Регистратор активности сотрудников FaceIT.

icons:
  - Teamgeist/icons/256x256/teamgeist.png

screenshots:
  - Teamgeist/screenshot.png

authors:
  - name: debkh
    url: https://github.com/debkh

links:
  - type: GitHub
    url: debkh/teamgeist-update-server
  - type: Download
    url: https://github.com/debkh/teamgeist-update-server/releases

desktop:
  Desktop Entry:
    Name: Teamgeist
    Comment: Регистратор активности сотрудников FaceIT.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: teamgeist
    X-AppImage-Version: 2.5.2
    X-AppImage-BuildId: acec57b0-7e00-11a8-3e10-09af458ba14f
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  license: CC0-1.0
  homepage: http://teamgeist.loc
  main: main.js
  files:
  - "./icons"
  - "./images"
  - "./addons"
  author:
    email: dmitry.oplachko@faceit.com.ua
  dependencies:
    electron-json-storage: "^4.1.0"
    electron-simple-updater: "^1.2.3"
    fs: 0.0.1-security
    js-sha256: "^0.3.0"
    remote: "^0.2.6"
    require: "^2.4.20"
---
