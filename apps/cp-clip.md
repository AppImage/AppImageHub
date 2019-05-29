---
layout: app

permalink: /cp-clip/
description: cp-clip

icons:
  - cp-clip/icons/128x128/cp-clip.png

screenshots:
  - cp-clip/screenshot.png

authors:
  - name: aklein13
    url: https://github.com/aklein13

links:
  - type: GitHub
    url: aklein13/cp-clip
  - type: Download
    url: https://github.com/aklein13/cp-clip/releases

desktop:
  Desktop Entry:
    Name: cp-clip
    Comment: cp-clip
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: cp-clip
    X-AppImage-Version: 0.3.2
    X-AppImage-BuildId: 29d75e60-fc9f-11a8-10f6-89e8dfc73c53
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: cp-clip
  main: "./main.prod.js"
  author:
    name: Akane
    email: arek.klein@gmail.com
    url: https://github.com/aklein13
  license: MIT
  dependencies:
    robotjs: "^0.5.1"
---
