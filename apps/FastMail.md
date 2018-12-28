---
layout: app

permalink: /FastMail/
description: FastMail AppImage

icons:
  - FastMail/icons/128x128/fastmail.png

screenshots:
  - FastMail/screenshot.png

authors:
  - name: aerosol
    url: https://github.com/aerosol

links:
  - type: GitHub
    url: aerosol/fastmail-appimage
  - type: Download
    url: https://github.com/aerosol/fastmail-appimage/releases

desktop:
  Desktop Entry:
    Name: fastmail
    Comment: FastMail AppImage
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: fastmail
    X-AppImage-Version: 1.0.0
    X-AppImage-BuildId: 8d7bff70-5df3-11a8-32b1-45ff68beab0c
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: main.js
  repository: https://github.com/aerosol/fastmail-appimage
  author: Adam Rutkowski <hq@mtod.org>
  license: CC0-1.0
---
