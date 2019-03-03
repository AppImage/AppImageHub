---
layout: app

permalink: /TinyRadio/
description: A radio app listen bbc radio and other radio
license: MIT

icons:
  - TinyRadio/icons/256x256/tinyradio.png

screenshots:
  - TinyRadio/screenshot.png

authors:
  - name: netroby
    url: https://github.com/netroby

links:
  - type: GitHub
    url: netroby/tiny-radio
  - type: Download
    url: https://github.com/netroby/tiny-radio/releases

desktop:
  Desktop Entry:
    Name: TinyRadio
    Comment: A radio app listen bbc radio and other radio
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: tinyradio
    StartupWMClass: TinyRadio
    X-AppImage-Version: 1.0.1
    Categories: Utility
    X-AppImage-BuildId: 1HnQJSMCBWmP5sAm2buUFk80syD
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  main: main.js
  dependencies: {}
  repository:
    type: git
    url: git+ssh://git@github.com/netroby/tiny-radio.git
  author: ZhiFeng Hu
  license: MIT
  bugs:
    url: https://github.com/netroby/tiny-radio/issues
  homepage: https://github.com/netroby/tiny-radio#readme
---
