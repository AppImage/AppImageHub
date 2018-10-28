---
layout: app

permalink: /LocalhostD/
description: LocalhostD takes care of launching your web app on your development machine.
license: MIT

icons:
  - LocalhostD/icons/512x512/localhostd.png

screenshots:
  - LocalhostD/screenshot.png

authors:
  - name: layerssss
    url: https://github.com/layerssss

links:
  - type: GitHub
    url: layerssss/localhostd
  - type: Download
    url: https://github.com/layerssss/localhostd/releases

desktop:
  Desktop Entry:
    Name: LocalhostD
    Comment: LocalhostD takes care of launching your web app on your development machine.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: localhostd
    StartupWMClass: LocalhostD
    X-AppImage-Version: 1.0.7.99
    Categories: Development
    X-AppImage-BuildId: 1C8zVZE00OQbqiC9G6nDGWhgEZG
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  main: bin/app.js
  bin:
    localhostd: bin/cli.js
  homepage: https://github.com/layerssss/localhostd
  browserslist:
  - ">0.2%"
  - not dead
  - not ie <= 11
  - not op_mini all
  repository:
    type: git
    url: git+https://github.com/layerssss/localhostd.git
  author:
    name: Michael Yin
    email: layerssss@gmail.com
  license: MIT
  bugs:
    url: https://github.com/layerssss/localhostd/issues
  dependencies:
    app-builder-lib: "^20.28.3"
    commander: "^2.18.0"
    electron-updater: "^3.1.2"
    express: "^4.16.3"
    http-proxy: "^1.17.0"
    lodash: "^4.17.11"
    mkdirp: "^0.5.1"
    node-forge: 0.7.6
    node-pty: 0.7.8
    portfinder: "^1.0.17"
    shell-env: "^2.1.0"
    shell-quote: "^1.6.1"
    update-notifier: "^2.5.0"
    username: "^4.0.0"
    which: "^1.3.1"
    ws: "^6.0.0"
  optionalDependencies:
    bufferutil: "^4.0.0"
    utf-8-validate: "^5.0.1"
---
