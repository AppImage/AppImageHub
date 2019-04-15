---
layout: app

permalink: /Humbug/
description: Humbug is a multi-platform barcode generator which can be used alongside our Germinate Scan application to generate sheets of user-defined barcodes to aid in the recording of data in the field or glasshouse.
license: Apache-2.0

icons:
  - Humbug/icons/256x256/humbug.png

screenshots:
  - Humbug/screenshot.png

authors:
  - name: sebastian-raubach
    url: https://github.com/sebastian-raubach

links:
  - type: GitHub
    url: sebastian-raubach/humbug-electron
  - type: Download
    url: https://github.com/sebastian-raubach/humbug-electron/releases

desktop:
  Desktop Entry:
    Name: Humbug
    Comment: Humbug is a multi-platform barcode generator which can be used alongside
      our Germinate Scan application to generate sheets of user-defined barcodes to
      aid in the recording of data in the field or glasshouse.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: humbug
    StartupWMClass: Humbug
    X-AppImage-Version: 2.19.4.32
    Categories: Utility
    X-AppImage-BuildId: 1JFyYL6BLXFhTAFRdHkV163Wgi8
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: Apache-2.0

electron:
  homepage: https://ics.hutton.ac.uk/get-humbug/
  repository:
    type: git
    url: https://github.com/sebastian-raubach/humbug-electron
  description: Humbug is a multi-platform barcode generator which can be used alongside
    our Germinate Scan application to generate sheets of user-defined barcodes to aid
    in the recording of data in the field or glasshouse.
  license: Apache-2.0
  main: "./dist/electron/main.js"
  dependencies:
    "@chenfengyuan/vue-qrcode": "^1.0.0"
    "@zxing/library": "^0.11.0"
    axios: "^0.18.0"
    bootstrap: "^4.3.1"
    bootstrap-vue: "^2.0.0-rc.11"
    compare-versions: "^3.4.0"
    jquery: "^3.3.1"
    sharp: "^0.21.3"
    uuid: "^3.3.2"
    vue: "^2.5.16"
    vue-barcode: "^1.2.0"
    vue-electron: "^1.0.6"
    vue-i18n: "^8.8.1"
    vue-material-design-icons: "^3.0.0"
    vue-router: "^3.0.1"
    vuex: "^3.0.1"
    vuex-electron: "^1.0.0"
---
