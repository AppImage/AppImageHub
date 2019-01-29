---
layout: app

permalink: /Chrysalis/
license: GPL-3.0
GPL-3.0

icons:
  - Chrysalis/icons/256x256/chrysalis.png

screenshots:
  - Chrysalis/screenshot.png

authors:
  - name: keyboardio
    url: https://github.com/keyboardio

links:
  - type: GitHub
    url: keyboardio/Chrysalis
  - type: Download
    url: https://github.com/keyboardio/Chrysalis/releases

desktop:
  Desktop Entry:
    Name: Chrysalis
    Comment: 
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: chrysalis
    StartupWMClass: Chrysalis
    X-AppImage-Version: 0.3.2
    Categories: Utility
    X-AppImage-BuildId: 1G3KkNPPFxlpWz0bFbII2HXq7Tz
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  author:
    name: Gergely Nagy
    email: algernon@keyboard.io
  homepage: https://github.com/keyboardio/Chrysalis
  husky:
    hooks:
      pre-commit: npm-run-all -p lint:all test
  dependencies:
    "@chrysalis-api/colormap": "~0.0.7"
    "@chrysalis-api/focus": "~0.0.8"
    "@chrysalis-api/hardware": "^0.0.2"
    "@chrysalis-api/keymap": "~0.0.13"
    "@material-ui/core": "^3.6.0"
    "@material-ui/icons": "^3.0.1"
    "@material-ui/lab": "^3.0.0-alpha.25"
    electron-devtools-installer: "^2.2.4"
    notistack: "^0.4.0"
    react: "^16.5.2"
    react-color: "^2.14.1"
    react-dom: "^16.5.2"
    react-localization: "^1.0.13"
    source-map-support: "^0.5.5"
    typeface-roboto: "^0.0.54"
    typeface-source-code-pro: "^0.0.71"
    usb: "^1.5.0"
  main: main.js
---
