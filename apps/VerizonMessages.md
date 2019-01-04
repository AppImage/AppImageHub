---
layout: app

permalink: /VerizonMessages/
description: Verizon Messages for linux

icons:
  - VerizonMessages/icons/512x512/verizonmessages.png

screenshots:
  - VerizonMessages/screenshot.png

authors:
  - name: kevinsarsen
    url: https://github.com/kevinsarsen

links:
  - type: GitHub
    url: kevinsarsen/verizon-messages
  - type: Download
    url: https://github.com/kevinsarsen/verizon-messages/releases

desktop:
  Desktop Entry:
    Name: VerizonMessages
    Comment: Verizon Messages for linux
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: verizonmessages
    StartupWMClass: VerizonMessages
    X-AppImage-Version: 1.1.5
    Categories: Office
    X-AppImage-BuildId: 1FGq8tlzA27SRUtcL5vcPKgaWhK
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
    url: https://github.com/kevinsarsen/verizon-messages.git
  author: Kevin Sarsen <kevinsarsen@pm.me>
  email: kevinsarsen@pm.me
  license: MIT
  dependencies:
    jimp: "^0.6.0"
    auto-launch: "^5.0.5"
    node-notifier: "^5.3.0"
---
