---
layout: app

permalink: /owltouch/
description: créateur de trajet pour cookieTouch

icons:
  - owltouch/icons/128x128/owltouch.png

screenshots:
  - owltouch/screenshot.png

authors:
  - name: Drigtime
    url: https://github.com/Drigtime

links:
  - type: GitHub
    url: Drigtime/owltouch
  - type: Download
    url: https://github.com/Drigtime/owltouch/releases

desktop:
  Desktop Entry:
    Name: owltouch
    Comment: créateur de trajet pour cookieTouch
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: owltouch
    StartupWMClass: owltouch
    X-AppImage-Version: 1.2.5
    Categories: Utility
    X-AppImage-BuildId: 1CPPekYP584MMpZ0alkBnVmIio3
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  productName: owltouch
  version: 1.2.5
  description: créateur de trajet pour cookieTouch
  main: __shim.js
  repository: https://github.com/drigtime/owltouch
  config:
    forge:
      make_targets:
        win32:
        - squirrel
        darwin:
        - zip
        linux:
        - deb
        - rpm
      electronPackagerConfig:
        packageManager: yarn
      electronWinstallerConfig:
        name: owltouch_new
      electronInstallerDebian: {}
      electronInstallerRedhat: {}
      github_repository:
        owner: ''
        name: ''
      windowsStoreConfig:
        packageName: ''
        name: owltouchnew
  dependencies:
    "@fortawesome/fontawesome-free": "^5.4.2"
    electron-compile: "^6.4.3"
    electron-squirrel-startup: "^1.0.0"
    electron-updater: "^3.1.2"
    esprima: "^4.0.1"
    i18next: "^11.9.1"
    image-size: "^0.6.3"
    jquery-i18next: "^1.2.1"
    leaflet: "^1.3.4"
    leaflet.markercluster: "^1.4.1"
    leaflet.markercluster.layersupport: "^2.0.1"
    typeface-roboto: "^0.0.54"
  originalMain: src/index.js
---
