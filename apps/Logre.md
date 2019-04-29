---
layout: app

permalink: /Logre/
description: A simple syslog reader
license: GPL-3.0

icons:
  - Logre/icons/512x512/logre.png

screenshots:
  - Logre/screenshot.png

authors:
  - name: yafp
    url: https://github.com/yafp

links:
  - type: GitHub
    url: yafp/logre
  - type: Download
    url: https://github.com/yafp/logre/releases

desktop:
  Desktop Entry:
    Name: Logre
    Comment: A simple syslog reader
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: logre
    StartupWMClass: Logre
    X-AppImage-Version: 1.1.0
    Categories: System
    X-AppImage-BuildId: 1KLdQ8n4dJaTDV5Ot6slWezPlhR
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  main: main.js
  repository: https://github.com/yafp/logre
  bugs:
    url: https://github.com/yafp/logre/issues
  author: yafp  <fidel@yafp.de>
  license: GPL-3.0
  dependencies: {}
---
