---
layout: app

permalink: /Puddle/
description: A web browser for full desktop apps.
license: MIT

icons:
  - Puddle/icons/128x128/puddle.png

screenshots:
  - Puddle/screenshot.png

authors:
  - name: geschafft-co
    url: https://github.com/geschafft-co

links:
  - type: GitHub
    url: geschafft-co/puddle
  - type: Download
    url: https://github.com/geschafft-co/puddle/releases

desktop:
  Desktop Entry:
    Name: Puddle
    Comment: A web browser for full desktop apps.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: puddle
    StartupWMClass: Puddle
    X-AppImage-Version: 0.1.1.17
    Categories: Utility
    X-AppImage-BuildId: 1IDrpu9d7v74s0dlPKRu8T5C6S3
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: A web browser for full desktop apps.
  author: Geschafft <hello@geschafft.co> (https://geschafft.co)
  repository: https://github.com/geschafft-co/puddle
  license: MIT
  main: src/main.js
---
