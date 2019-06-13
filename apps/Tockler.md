---
layout: app

permalink: /Tockler/
description: Automatically track applications usage and working time
license: GPL-2.0

icons:
  - Tockler/icons/128x128/tockler.png

screenshots:
  - Tockler/screenshot.png

authors:
  - name: MayGo
    url: https://github.com/MayGo

links:
  - type: GitHub
    url: MayGo/tockler
  - type: Download
    url: https://github.com/MayGo/tockler/releases

desktop:
  Desktop Entry:
    Name: Tockler
    Comment: Automatically track applications usage and working time
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: tockler
    StartupWMClass: Tockler
    X-AppImage-Version: 3.4.8.227
    Categories: Utility
    X-AppImage-BuildId: 1Kh1z7TkHa0QFNXEOiV33Op9ytY
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-2.0

electron:
  author: Maigo Erit <maigo.erit@gmail.com>
  license: GPL-2.0
  main: dist/index.js
  repository:
    type: git
    url: git@github.com:MayGo/tockler.git
  dependencies:
    active-win: "^5.0.0"
    compare-versions: "^3.4.0"
    cpx: "^1.5.0"
    electron-context-menu: 0.12.0
    electron-devtools-installer: "^2.2.4"
    electron-is-dev: "^1.1.0"
    electron-log: "^3.0.5"
    electron-squirrel-startup: "^1.0.0"
    electron-store: 3.2.0
    electron-updater: 4.0.6
    hazardous: "^0.3.0"
    menubar: "^5.2.3"
    moment: 2.24.0
    multiline: "^2.0.0"
    node-notifier: "^5.4.0"
    os-locale: "^3.1.0"
    randomcolor: 0.5.4
    reflect-metadata: "^0.1.13"
    requirejs: "^2.3.6"
    sequelize: 5.3.5
    sequelize-mock: 0.10.2
    sequelize-typescript: "^0.6.9"
    sqlite3: 4.0.6
  peerDependencies: {}
  jest:
    globals:
      __TEST__: true
    unmockedModulePathPatterns:
    - babel
    - "<rootDir>/node_modules/source-map-support"
    moduleFileExtensions:
    - ts
    - js
    setupTestFrameworkScriptFile: "<rootDir>/util/jest-setup.js"
    transform:
      "\\.(ts|tsx)$": "<rootDir>/node_modules/ts-jest/preprocessor.js"
    testRegex: "/__tests__/.*\\.test\\.ts$"
    testEnvironment: node
---
