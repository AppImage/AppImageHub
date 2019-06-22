---
layout: app

permalink: /noia-node-gui/
description: Node GUI
license: LGPL-2.1

icons:
  - noia-node-gui/icons/569x569/noia-node-gui.png

screenshots:
  - noia-node-gui/screenshot.png

authors:
  - name: noia-network
    url: https://github.com/noia-network

links:
  - type: GitHub
    url: noia-network/noia-node-gui
  - type: Download
    url: https://github.com/noia-network/noia-node-gui/releases

desktop:
  Desktop Entry:
    Name: NOIA
    Comment: Node GUI
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: noia-node-gui
    X-AppImage-Version: 0.4.0
    X-AppImage-BuildId: 3e274e00-89fb-11a8-1fbc-5d4c1e3f5fc6
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: LGPL-2.1

electron:
  homepage: http://noia.network
  main: main.js
  author:
    name: NOIA Network Limited
    email: info@noia.network
  license: LGPL-2.1
  dependencies:
    "@angular/animations": "^5.2.9"
    "@noia-network/node": 0.2.6
    date-fns: "^1.29.0"
    diskusage-ng: "^0.2.3"
    ngx-toastr: "^8.3.0"
    os: "^0.1.1"
    "@types/opn": "^5.1.0"
    electron-updater: "^3.0.1"
    opn: "^5.3.0"
    randombytes: "^2.0.6"
    request: "^2.85.0"
    typeface-roboto: 0.0.54
    typeface-roboto-mono: 0.0.54
  repository:
    type: git
    url: git+https://github.com/noia-network/noia-node-gui.git
---
