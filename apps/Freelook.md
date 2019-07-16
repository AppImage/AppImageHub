---
layout: app

permalink: /Freelook/
license: MIT

icons:
  - Freelook/icons/128x128/electron-outlook.png

screenshots:
  - Freelook/screenshot.png

authors:
  - name: eNkru
    url: https://github.com/eNkru

links:
  - type: GitHub
    url: eNkru/freelook
  - type: Download
    url: https://github.com/eNkru/freelook/releases

desktop:
  Desktop Entry:
    Name: electron-outlook
    Comment: 
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: electron-outlook
    X-AppImage-Version: 0.1.0
    X-AppImage-BuildId: 5cbcbba0-0c80-11a8-0f6f-a9cb85b0669a
    Categories: Office
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  main: src/main.js
  author: Howard Ju <howard.ju@outlook.com>
  repository: https://github.com/eNkru/electron-outlook
  license: MIT
---
