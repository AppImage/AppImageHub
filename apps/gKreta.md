---
layout: app

permalink: /gKreta/
description: Based on Electron, this is a replacement for KRÉTA's web interface.
license: GPL-3.0

icons:
  - gKreta/icons/128x128/gkreta.png

screenshots:
  - gKreta/screenshot.png

authors:
  - name: thegergo02
    url: https://github.com/thegergo02

links:
  - type: GitHub
    url: thegergo02/gKreta
  - type: Download
    url: https://github.com/thegergo02/gKreta/releases

desktop:
  Desktop Entry:
    Name: gKreta
    Comment: Based on Electron, this is a replacement for KRÉTA's web interface.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: gkreta
    StartupWMClass: gKreta
    X-AppImage-Version: 0.7.0
    Categories: Education
    X-AppImage-BuildId: 1HBU7D4cC6DPwrXYKGpZJOfkrC2
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
    (Written in Electron)
  main: main.js
  author: thegergo02
  license: GPL-3.0
  dependencies:
    keytar: "^4.4.0"
---
