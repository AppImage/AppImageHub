---
layout: app

permalink: /DSH-UMP/
description: tenant management portal for DSH

icons:
  - DSH-UMP/icons/128x128/dsh-ump.png

screenshots:
  - DSH-UMP/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: DSH-UMP
    Comment: tenant management portal for DSH
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: dsh-ump
    X-AppImage-Version: 1.2.0
    X-AppImage-BuildId: c10a1d30-8be4-11a8-1bd9-f9753aaf066c
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  author:
    name: klarrio
  dependencies:
    electron-updater: 2.20.1
    electron-log: 2.2.14
    keytar: 4.2.1
---
