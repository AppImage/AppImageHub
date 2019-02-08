---
layout: app

permalink: /google-translate-desktop/
description: a desktop version of google translation using electron
license: MIT

icons:
  - google-translate-desktop/icons/128x128/google-translation-desktop.png

screenshots:
  - google-translate-desktop/screenshot.png

authors:
  - name: zhuzilin
    url: https://github.com/zhuzilin

links:
  - type: GitHub
    url: zhuzilin/google-translate-desktop
  - type: Download
    url: https://github.com/zhuzilin/google-translate-desktop/releases

desktop:
  Desktop Entry:
    Name: google-translation-desktop
    Comment: a desktop version of google translation using electron
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: google-translation-desktop
    StartupWMClass: google-translation-desktop
    X-AppImage-Version: 1.0.0
    Categories: Utility
    X-AppImage-BuildId: 19x9ALSHQDNdBDSmj3L3KCKykQE
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  main: src/main.js
  author: zhuzilin
  license: MIT
  dependencies:
    axios: "^0.18.0"
---
