---
layout: app

permalink: /ganjoor-electron/

icons:
  - ganjoor-electron/icons/128x128/ganjoor-electron.png

screenshots:
  - ganjoor-electron/screenshot.png

authors:
  - name: moeen
    url: https://github.com/moeen

links:
  - type: GitHub
    url: moeen/ganjoor-electron
  - type: Download
    url: https://github.com/moeen/ganjoor-electron/releases

desktop:
  Desktop Entry:
    Name: ganjoor-electron
    Comment: 
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: ganjoor-electron
    StartupWMClass: ganjoor-electron
    X-AppImage-Version: 0.1.1.24
    Categories: Utility
    X-AppImage-BuildId: 1HtL2mdpNbUemiHG5NRsA8AblTq
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  dependencies:
    "@fortawesome/fontawesome-svg-core": "^1.2.12"
    "@fortawesome/free-solid-svg-icons": "^5.6.3"
    "@fortawesome/vue-fontawesome": "^0.1.4"
    bulma-rtl: "^0.7.1"
    decompress: "^4.2.0"
    pg-hstore: "^2.3.2"
    sequelize: "^4.42.0"
    sqlite3: "^4.0.4"
    tedious: "^3.0.1"
    vue: "^2.5.21"
    vue-router: "^3.0.1"
    vuex: "^3.0.1"
  main: background.js
---
