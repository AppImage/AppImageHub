---
layout: app

permalink: /Listen_1/
description: One for all free music in China

icons:
  - Listen_1/icons/128x128/listen1.png

screenshots:
  - Listen_1/screenshot.png

authors:
  - name: listen1
    url: https://github.com/listen1

links:
  - type: GitHub
    url: listen1/listen1_desktop
  - type: Download
    url: https://github.com/listen1/listen1_desktop/releases

desktop:
  Desktop Entry:
    Name: Listen1
    Comment: One for all free music in China
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: listen1
    StartupWMClass: Listen1
    X-AppImage-Version: 2.0.0
    Categories: Utility
    X-AppImage-BuildId: 1EiBZpZgAwg6quuqGMCJ0BOvwFD
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: main.js
  repository:
    type: git
    url: git+https://github.com/listen1/listen1_desktop.git
  author: Listen 1 <githublisten1@gmail.com>
  license: MIT
  bugs:
    url: https://github.com/listen1/listen1_desktop/issues
  homepage: https://github.com/listen1/listen1_desktop#readme
---
