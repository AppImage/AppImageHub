---
layout: app

permalink: /World_Mobile_Coin/
description: WorldMobileCoin © WMCC Desktop Application
license: MIT

icons:
  - World_Mobile_Coin/icons/128x128/wmcc-desktop.png

screenshots:
  - World_Mobile_Coin/screenshot.png

authors:
  - name: WorldMobileCoin
    url: https://github.com/WorldMobileCoin

links:
  - type: GitHub
    url: WorldMobileCoin/wmcc-desktop
  - type: Download
    url: https://github.com/WorldMobileCoin/wmcc-desktop/releases

desktop:
  Desktop Entry:
    Name: wmcc-desktop
    Comment: WorldMobileCoin © WMCC Desktop Application
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: wmcc-desktop
    X-AppImage-Version: 1.1.1-beta.7
    X-AppImage-BuildId: ca585900-1ad3-11a9-0797-b144951661e7
    Categories: Network
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  bugs:
    url: https://github.com/WorldMobileCoin/wmcc-desktop/issues
  bundleDependencies: false
  dependencies:
    electron-updater: 2.16.3
    leveldown: 1.7.2
    node-x15: "*"
    secp256k1: 3.3.0
    socket.io: 2.0.3
    socket.io-client: 2.0.3
    wmcc-core: "*"
    wmcc-credential: "*"
    wmcc-exchange-client: "*"
    wmcc-native: "*"
    wmcc-node: "*"
  deprecated: false
  description: WorldMobileCoin © WMCC Desktop Application
  homepage: https://github.com/WorldMobileCoin/wmcc-desktop
  license: MIT
  main: index.js
  name: wmcc-desktop
  optionalDependencies:
    wmcc-native: "*"
  productName: wmcc-desktop
  release: 15 Jan 2019
  repository:
    type: git
    url: git://github.com/WorldMobileCoin/wmcc-desktop.git
  version: 1.1.1-beta.7
---
