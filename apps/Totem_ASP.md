---
layout: app

permalink: /Totem_ASP/
description: Totem ASP
license: MIT

icons:
  - Totem_ASP/icons/128x128/totem_asp.png

screenshots:
  - Totem_ASP/screenshot.png

authors:
  - name: Guccieii
    url: https://github.com/Guccieii

links:
  - type: GitHub
    url: Guccieii/Totem_ASP
  - type: Download
    url: https://github.com/Guccieii/Totem_ASP/releases

desktop:
  Desktop Entry:
    Name: Totem ASP
    Comment: Totem ASP
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: totem_asp
    StartupWMClass: Totem ASP
    X-AppImage-Version: 0.0.51
    Categories: Utility
    X-AppImage-BuildId: 1LM6wmJYGEBlZUGPFnU70SRVdpR
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: Totem ASP
  author:
    name: 6Mobile SRL
    email: v.guccione@6mobile.mobi
    url: https://6mobile.mobi
  private: true
  homepage: "./"
  main: build/electron.js
  repository: https://github.com/Guccieii/Totem_ASP
  dependencies:
    "@fortawesome/fontawesome-svg-core": "^1.2.17"
    "@fortawesome/free-solid-svg-icons": "^5.8.1"
    "@fortawesome/react-fontawesome": "^0.1.4"
    "@redux-offline/redux-offline": "^2.5.1"
    auto-launch: "^5.0.5"
    axios: "^0.18.0"
    bootstrap: "^4.3.1"
    bootstrap-italia: "^1.2.6"
    connected-react-router: 4.5.0
    cross-env: "^5.2.0"
    design-react-kit: "^2.10.0"
    electron-is-dev: "^1.1.0"
    electron-simple-updater: "^1.5.0"
    electron-updater: "^4.0.6"
    npm: "^6.9.0"
    react: 16.8.6
    react-bootstrap: "^1.0.0-beta.8"
    react-countdown-clock: "^2.6.0"
    react-dom: 16.8.6
    react-idle-timer: "^4.2.5"
    react-redux: 5.1.1
    react-router: 4.4.0-beta.8
    react-router-dom: 4.4.0-beta.8
    react-simple-keyboard: "^1.22.0"
    redux: 4.0.1
    redux-logger: "^3.0.6"
    redux-react-session: "^2.5.0"
    redux-thunk: 2.3.0
    sanitize.css: 7.0.3
    serve: 10.1.2
  browserslist:
  - ">0.2%"
  - not dead
  - not ie <= 11
  - not op_mini all
---
