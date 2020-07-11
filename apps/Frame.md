---
layout: app

permalink: /Frame/
description: An Ethereum Interface
license: GPL-3.0

icons:
  - Frame/icons/512x512/frame.png

screenshots:
  - Frame/screenshot.png

authors:
  - name: floating
    url: https://github.com/floating

links:
  - type: GitHub
    url: floating/frame
  - type: Download
    url: https://github.com/floating/frame/releases

desktop:
  Desktop Entry:
    Name: Frame
    Comment: An Ethereum Interface
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: frame
    StartupWMClass: Frame
    X-AppImage-Version: 0.1.1
    Categories: Utility
    X-AppImage-BuildId: 1H0LtORsJ90B8qVPgdx0eSkJaCc
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  main: main
  jest:
    testPathIgnorePatterns:
    - "/node_modules/"
    - "/build/"
    - "/bundle/"
    - "/dist/"
  author:
    name: Jordan Muir
    email: jordan@frame.sh
    url: https://frame.sh
  license: GPL-3.0
  dependencies:
    "@githubprimer/octicons-react": 8.1.3
    "@ledgerhq/hw-app-eth": 4.24.0
    "@ledgerhq/hw-transport-node-hid": 4.24.0
    auto-launch: 5.0.5
    babel-polyfill: 6.26.0
    bip32-path: 0.4.2
    cross-env: 5.2.0
    electron-log: 2.2.17
    electron-positioner: 4.1.0
    electron-store: 2.0.0
    electron-updater: 3.1.6
    eth-provider: 0.2.1
    ethereumjs-tx: 1.3.7
    ethereumjs-util: 6.0.0
    hdkey: 1.1.0
    node-hid: 0.7.4
    query-string: 6.2.0
    react: 16.6.3
    react-dom: 16.6.3
    react-restore: 0.3.0
    react-transition-group: 1.2.1
    semver: 5.6.0
    trezor.js: 6.19.0
    usb-detection: 4.1.0
    uuid: 3.3.2
    web3-utils: 1.0.0-beta.36
    ws: 6.1.2
  standard:
    parser: babel-eslint
  repository: github:floating/frame
---
