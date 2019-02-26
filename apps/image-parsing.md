---
layout: app

permalink: /image-parsing/
description: An electron-vue project
license: MIT

icons:
  - image-parsing/icons/358x256/image-parsing.png

screenshots:
  - image-parsing/screenshot.png

authors:
  - name: mubaidr
    url: https://github.com/mubaidr

links:
  - type: GitHub
    url: mubaidr/image-parsing
  - type: Download
    url: https://github.com/mubaidr/image-parsing/releases

desktop:
  Desktop Entry:
    Name: image-parsing
    Comment: An electron-vue project
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: image-parsing
    StartupWMClass: image-parsing
    X-AppImage-Version: 0.0.1.502
    Categories: Utility
    X-AppImage-BuildId: 1Bpj6ImL1ES8iLDYsFVZBnqHYeE
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  dependencies:
    brain.js: "^1.4.2"
    bulma-addons: "^0.1.12"
    bulma-fluent: "^0.3.14"
    cheerio: 1.0.0-rc.2
    downloadjs: "^1.4.7"
    electron-store: "^2.0.0"
    fast-glob: "^2.2.3"
    javascript-barcode-reader: "^0.4.2"
    pdfmake: "^0.1.38"
    physical-cpu-count: "^2.0.0"
    sharp: "^0.21.0"
    vue: "^2.5.17"
    vue-router: "^3.0.1"
    vuex: "^3.0.1"
  description: An electron-vue project
  jest:
    bail: true
    collectCoverage: false
    collectCoverageFrom:
    - src/utilities/**/*.js
    - "!src/utilities/tmp/"
    coverageDirectory: __coverage__
    globalSetup: ''
    globals: {}
    setupFiles: []
    testPathIgnorePatterns:
    - __tests__/.eslintrc.js
  license: MIT
  main: "./dist/electron/main.js"
  name: image-parsing
  repository:
    type: git
    url: git+https://github.com/mubaidr/image-parsing.git
  version: 0.0.1
---
