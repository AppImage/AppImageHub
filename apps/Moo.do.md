---
layout: app

permalink: /Moo.do/
description: Organize your way

icons:
  - Moo.do/icons/256x256/moo.do.png

screenshots:
  - Moo.do/screenshot.png

authors:
  - name: MooDoApp
    url: https://github.com/MooDoApp

links:
  - type: GitHub
    url: MooDoApp/MooDoApp.github.io
  - type: Download
    url: https://github.com/MooDoApp/MooDoApp.github.io/releases

desktop:
  Desktop Entry:
    Name: Moo.do
    Comment: Organize your way
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: moo.do
    StartupWMClass: Moo.do
    X-AppImage-Version: 1.2.1
    Categories: Office
    X-AppImage-BuildId: 1FqPgKe1da0FwYYHjx8vXqCSxjs
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  author:
    name: Moo.do LLC
    email: contact@moo.do
  productName: Moo.do
  homepage: https://www.moo.do
  description: Organize your way
  dependencies:
    chokidar: "^2.0.4"
    electron-dl: "^1.10.0"
    electron-updater: "^4.0.1"
---
