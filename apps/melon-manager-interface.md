---
layout: app

permalink: /melon-manager-interface/
description: Melon interface

icons:
  - melon-manager-interface/icons/512x512/@melonprojectmanager-interface.png

screenshots:
  - melon-manager-interface/screenshot.png

authors:
  - name: melonproject
    url: https://github.com/melonproject

links:
  - type: GitHub
    url: melonproject/melon-lab
  - type: Download
    url: https://github.com/melonproject/melon-lab/releases

desktop:
  Desktop Entry:
    Name: Melon Manager Interface
    Comment: Melon interface
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: "@melonprojectmanager-interface"
    StartupWMClass: Melon Manager Interface
    X-AppImage-Version: 0.8.4
    Categories: Finance
    X-AppImage-BuildId: 18vKbA7e9hWIhkRchR1RZSzeVvN
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  version: 0.8.4
  private: true
  license: AGPL-3.0
  main: main.js
  author: Melonport <team@melonport.com>
  dependencies:
    "@melonproject/graphql-schema": "*"
    "@melonproject/melon.js": "*"
    apollo-cache-inmemory: "^1.1.12"
    apollo-client: "^2.3.1"
    apollo-link: "^1.2.1"
    apollo-link-http: "^1.5.3"
    apollo-link-schema: "^1.0.6"
    apollo-link-ws: "^1.0.7"
    bignumber.js: 4.1.0
    copy-webpack-plugin: "^4.5.2"
    cross-env: "^5.1.5"
    debug: 2.6.9
    dotenv-extended: "^2.0.1"
    electron-debug: "^1.5.0"
    electron-devtools-installer: "^2.2.4"
    ethers: "^2.1.3"
    find-up: "^3.0.0"
    flat: "^4.0.0"
    graphql: "^0.13.2"
    graphql-tag: "^2.9.2"
    graphql-tools: "^2.24.0"
    history: "^4.7.2"
    keytar: "^4.2.1"
    moment: "^2.20.1"
    next: "^6.0.0"
    next-with-apollo: "^3.1.2"
    prop-types: "^15.6.1"
    ramda: "^0.25.0"
    raven-js: "^3.25.2"
    react: "^16.2.0"
    react-apollo: "^2.1.3"
    react-dom: "^16.2.0"
    react-highlighter: "^0.4.2"
    react-modal: "^3.1.10"
    react-redux: "^5.0.6"
    recompose: "^0.27.1"
    redux: "^3.7.2"
    redux-first-router: 0.0.4-rudy
    redux-first-router-link: "^1.4.2"
    redux-form: "^7.2.0"
    redux-saga: "^0.16.0"
    rxjs: "^5.5.8"
    semantic-ui-react: "^0.77.1"
    slugify: "^1.2.9"
    subscriptions-transport-electron: https://github.com/fubhy/subscriptions-transport-electron.git#dist
    subscriptions-transport-ws: "^0.9.7"
    svg-sprite-loader: "^3.8.0"
    websocket: "^1.0.26"
---
