---
layout: app

permalink: /Qri/
description: qri (“query”) frontend application
license: MIT

icons:
  - Qri/icons/256x256/qri-webapp.png

screenshots:
  - Qri/screenshot.png

authors:
  - name: qri-io
    url: https://github.com/qri-io

links:
  - type: GitHub
    url: qri-io/frontend
  - type: Download
    url: https://github.com/qri-io/frontend/releases

desktop:
  Desktop Entry:
    Name: qri
    Comment: qri (“query”) frontend application
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: qri-webapp
    StartupWMClass: qri
    X-AppImage-Version: 0.7.0
    Categories: Utility
    X-AppImage-BuildId: 1Gk7Hv09xlemfzs8kDQ7TFQGf53
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: qri ("query") frontend application
  main: "./main.prod.js"
  author:
    name: Brendan O'Brien
    email: sparkle_pony_2000@qri.io
    url: github.com/qri-io
  license: MIT
  dependencies: {}
---
