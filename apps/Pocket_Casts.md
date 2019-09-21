---
layout: app

permalink: /Pocket_Casts/
description: Electron wrapper around the Pocket Casts web app with support for MPRIS (media controls)
license: MIT

icons:
  - Pocket_Casts/icons/128x128/pocket-casts-linux.png

screenshots:
  - Pocket_Casts/screenshot.png

authors:
  - name: jgierer12
    url: https://github.com/jgierer12

links:
  - type: GitHub
    url: jgierer12/pocket-casts-linux
  - type: Download
    url: https://github.com/jgierer12/pocket-casts-linux/releases

desktop:
  Desktop Entry:
    Name: Pocket Casts
    Comment: Electron wrapper around the Pocket Casts web app with support for MPRIS
      (media controls)
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: pocket-casts-linux
    StartupWMClass: Pocket Casts
    X-AppImage-Version: 1.2.1
    Categories: AudioVideo
    X-AppImage-BuildId: 1J3DSggbjNxAFdGViuhemlSJQAF
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  license: MIT
  description: Electron wrapper around the Pocket Casts web app with support for MPRIS
    (media controls)
  homepage: https://github.com/jgierer12/pocket-casts-linux
  author:
    name: Jonas Gierer
    email: jgierer12@gmail.com
  repository:
    type: git
    url: https://github.com/jgierer12/pocket-casts-linux.git
  main: src/index.js
  dependencies:
    dom-loaded: "^1.0.1"
    electron-is-dev: "^1.0.1"
    electron-window-state: "^5.0.3"
    mpris-service: "^2.0.0"
    select-dom: "^4.1.3"
---
