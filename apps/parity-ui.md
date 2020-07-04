---
layout: app

permalink: /parity-ui/
description: The Electron app for Parity UI
license: GPL-3.0

icons:
  - parity-ui/icons/512x512/parity-ui.png

screenshots:
  - parity-ui/screenshot.png

authors:
  - name: ellaism
    url: https://github.com/ellaism

links:
  - type: GitHub
    url: ellaism/shell
  - type: Download
    url: https://github.com/ellaism/shell/releases

desktop:
  Desktop Entry:
    Name: Ellaism Shell
    Comment: The Electron app for Parity UI
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: parity-ui
    X-AppImage-Version: 0.3.2.21
    X-AppImage-BuildId: 7dfc0b30-8cfb-11a8-141e-2dc212053642
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  main: ".build/electron.js"
  jsnext:main: ".build/electron.js"
  author:
    name: Parity Technologies
    email: admin@parity.io
  maintainers:
  - Jaco Greeff
  - Nicolas Gotchac
  license: GPL-3.0
  repository:
    type: git
    url: git+https://github.com/parity-js/shell.git
  parity:
    channel: beta
  dependencies:
    "@parity/api": 2.1.20
    "@parity/mobx": 1.1.2
    "@parity/plugin-signer-account": github:parity-js/plugin-signer-account#05294dce59b7cd7c4f1b26dc604fc6a04dd02bc8
    "@parity/plugin-signer-default": github:parity-js/plugin-signer-default#dcf8cf23bb050070b6a691413b974b5c2d7d1ce6
    "@parity/plugin-signer-hardware": github:parity-js/plugin-signer-hardware#e8b8a4e67adc37870e370d22805632d08012b9ee
    "@parity/plugin-signer-qr": github:parity-js/plugin-signer-qr#c275ba13524e9f6759079fabd10faf49cc00cfc0
    "@parity/shared": 2.2.28
    "@parity/ui": 3.1.9
    axios: 0.18.0
    command-exists: 1.2.2
    commander: 2.15.1
    electron-dl: 1.11.0
    follow-redirects: 1.5.0
    fs-extra: 6.0.1
    is-electron: 2.1.0
    js-sha3: 0.7.0
    keythereum: 1.0.2
    lodash.flatten: 4.4.0
    lodash.omitby: 4.6.0
    lodash.throttle: 4.1.1
    lodash.uniq: 4.5.0
    material-ui: 0.16.5
    mobx: 3.3.2
    mobx-react: 4.3.5
    prop-types: 15.5.10
    query-string: 5.0.1
    react: 16.1.1
    react-dom: 16.1.1
    react-intl: 2.4.0
    react-markdown: 3.0.2
    react-progress-bar.js: 0.2.3
    react-redux: "^5.0.6"
    react-router: 3.2.0
    react-router-redux: 4.0.8
    react-tap-event-plugin: 3.0.2
    react-transition-group: 2.2.1
    redux: 3.7.2
    semantic-ui-react: 0.77.0
    solc: ngotchac/solc-js
    store: 1.3.20
    unzipper: 0.8.14
    util.promisify: 1.0.0
---
