---
layout: app

permalink: /LAMD/
description: Browse, search and manage accounts, replays and more without the need of an actual account on Live.me.
license: AGPL-3.0

icons:
  - LAMD/icons/1024x1024/lamd.png

screenshots:
  - LAMD/screenshot.png

authors:
  - name: thecoder75
    url: https://github.com/thecoder75

links:
  - type: GitHub
    url: thecoder75/lamd
  - type: Download
    url: https://github.com/thecoder75/lamd/releases

desktop:
  Desktop Entry:
    Name: LAMD
    Comment: Browse, search and manage accounts, replays and more without the need of
      an actual account on Live.me.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: lamd
    StartupWMClass: LAMD
    X-AppImage-Version: 3.1.0
    Categories: Network
    X-AppImage-BuildId: 1GItQv9b3IVwZe8rAKOG1r1f1U2
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: AGPL-3.0

electron:
    downloads them.
  homepage: https://github.com/thecoder75/lamd
  main: index.js
  repository:
    type: git
    url: https://github.com/thecoder75/lamd
  author: TheCoder75
  license: AGPLv3
  dependencies:
    async: "^2.6.1"
    concat-files: "^0.1.1"
    fs: 0.0.1-security
    path: "^0.12.7"
    platform: "^1.3.5"
    request: "^2.88.0"
    request-promise-native: "^1.0.5"
---
