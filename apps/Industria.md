---
layout: app

permalink: /Industria/
description: An electron-vue project

icons:
  - Industria/icons/256x256/industria.png

screenshots:
  - Industria/screenshot.png

authors:
  - name: mauricioaznar
    url: https://github.com/mauricioaznar

links:
  - type: GitHub
    url: mauricioaznar/InoElectron
  - type: Download
    url: https://github.com/mauricioaznar/InoElectron/releases

desktop:
  Desktop Entry:
    Name: Industria
    Comment: An electron-vue project
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: industria
    X-AppImage-Version: 1.0.34.154
    X-AppImage-BuildId: 170b5410-710e-11a9-1b82-fd11b9c92b12
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: An electron-vue project
  license: 
  main: "./dist/electron/main.js"
  dependencies:
    axios: "^0.16.1"
    bootstrap: "^4.1.1"
    bootstrap-vue: "^2.0.0-rc.11"
    chart.js: "^2.7.2"
    electron-updater: "^2.23.3"
    font-awesome: "^4.7.0"
    jquery: "^3.3.1"
    lodash: "^4.17.10"
    mau-vue-components: "^0.12.0"
    moment: "^2.22.2"
    node-sass: "^4.9.0"
    normalize.css: "^8.0.0"
    sass-loader: "^7.0.3"
    text-mask-addons: "^3.7.2"
    vee-validate: "^2.2.0"
    vue: "^2.3.3"
    vue-chartjs: "^3.3.2"
    vue-electron: "^1.0.6"
    vue-full-calendar: "^2.6.1"
    vue-fullcalendar: "^1.0.9"
    vue-notification: "^1.3.12"
    vue-resource: "^1.5.1"
    vue-router: "^2.5.3"
    vue-select: "^2.4.0"
    vue-spinner: "^1.0.3"
    vue-text-mask: "^6.1.1"
    vue2-editor: "^2.5.0"
    vuetable-2: "^1.7.5"
    vuex: "^2.3.1"
    vuex-router-sync: "^5.0.0"
---
