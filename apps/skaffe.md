---
layout: app

permalink: /skaffe/
description: blablabla
license: MIT

icons:
  - skaffe/icons/128x128/skaffe.png

screenshots:
  - skaffe/screenshot.png

authors:
  - name: patbonecrusher
    url: https://github.com/patbonecrusher

links:
  - type: GitHub
    url: patbonecrusher/skaffe
  - type: Download
    url: https://github.com/patbonecrusher/skaffe/releases

desktop:
  Desktop Entry:
    Name: skaffe
    Comment: blablabla
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: skaffe
    StartupWMClass: skaffe
    X-AppImage-Version: 0.0.0
    Categories: Utility
    X-AppImage-BuildId: 1JhRPkECdx62CmJMBZYUTvFzYZt
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  homepage: http://www.google.com
  description: blablabla
  author: PatLaplante Software Consulting <laplante.patrick@gmail.com> (https://patlaplante.com)
  repository:
    type: git
    url: https://github.com/patbonecrusher/skaffe.git
  dependencies:
    electron-builder-squirrel-windows: "^20.40.0"
    source-map-support: "^0.5.12"
  main: main.js
---
