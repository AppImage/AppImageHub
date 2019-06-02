---
layout: app

permalink: /Panacea_Wallet/
description: The official desktop wallet for the Panacea platform. Look for contribution or source? Visit this site: https://github.com/panacea-coin/panacea-wallet#readme
license: MIT

icons:
  - Panacea_Wallet/icons/1025x1087/panacea-desktop-wallet.png

screenshots:
  - Panacea_Wallet/screenshot.png

authors:
  - name: panacea-coin
    url: https://github.com/panacea-coin

links:
  - type: GitHub
    url: panacea-coin/panacea-wallet
  - type: Download
    url: https://github.com/panacea-coin/panacea-wallet/releases

desktop:
  Desktop Entry:
    Name: Panacea Desktop Wallet
    Comment: 'The official desktop wallet for the Panacea platform. Look for contribution
      or source? Visit this site: https://github.com/panacea-coin/panacea-wallet'
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: panacea-desktop-wallet
    StartupWMClass: Panacea Desktop Wallet
    X-AppImage-Version: 1.0.1
    MimeType: x-scheme-handler/panacea
    Categories: Utility
    X-AppImage-BuildId: 1GmpEdzjIv454LtCytPSzHjkZvn
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
    or source? Visit this site: https://github.com/panacea-coin/panacea-wallet#readme'
  main: "./main.js"
  repository:
    type: git
    url: git+https://github.com/panacea-coin/panacea-wallet.git
  author: PanaceaPlatform <info@panacea.io>
  license: MIT
  bugs:
    url: https://github.com/panacea-coin/panacea-wallet/issues
  homepage: https://www.panacea-coin.org
  dependencies:
    "@uirouter/angularjs": "^1.0.11"
    about-window: "^1.11.0"
    ajv: "^6.6.2"
    angular: "^1.6.1"
    angular-animate: "^1.6.1"
    angular-aria: "^1.6.1"
    angular-gettext: "^2.3.6"
    angular-material: "^1.1.5"
    angular-material-data-table: git://github.com/daniel-nagy/md-data-table.git#master
    angular-messages: "^1.5.5"
    angular-qrcode: "^7.2.0"
    ark-qrcode: 0.0.6
    async: "^2.5.0"
    bip39: "^2.2.0"
    csv-parse: "^2.0.0"
    electron-window-state: "^4.1.1"
    elemon: "^5.0.3"
    jsqr: "^0.2.2"
    ledgerco: github:ledgerhq/ledger-node-js-api#6cde5978b9d0a4922f0d33520b16cc2184559ebc
    moment-range: "^3.1.0"
    moment-timezone: "^0.5.14"
    ng-infinite-scroll: "^1.3.0"
    node-vibrant: "^3.0.0-alpha.2"
    panacea-js: 1.0.3
    q: "^1.5.0"
    qrcode-generator: "^1.3.1"
    rss-parser: "^2.10.8"
---
