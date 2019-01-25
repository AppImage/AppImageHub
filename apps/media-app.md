---
layout: app

permalink: /media-app/
description: Media App

screenshots:
  - media-app/screenshot.png

authors:
  - name: SanderRonde
    url: https://github.com/SanderRonde

links:
  - type: GitHub
    url: SanderRonde/media-app
  - type: Install
    url: https://github.com/SanderRonde/media-app/releases

desktop:
  Desktop Entry:
    Name: Media App
    Comment: Media App
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: media-app
    X-AppImage-Version: 3.0.0
    X-AppImage-BuildId: 04611c70-9715-11a7-1853-758a46563049
    Categories: Video
  AppImageHub:
    X-AppImage-UpdateInformation: 
    X-AppImage-Type: 1
    X-AppImage-Architecture: x86_64

electron:
  main: "./out/app.js"
  repository:
    type: git
    url: git+https://github.com/SanderRonde/media-app.git
  author:
    name: Sander Ronde
    email: awsdfgvhbjn@gmail.com
  license: MIT
  bugs:
    url: https://github.com/SanderRonde/media-app/issues
  homepage: https://github.com/SanderRonde/media-app#readme
  dependencies:
    abp-filter-parser: "^0.2.0"
    electron-context-menu: "^0.9.1"
    electron-updater: "^2.8.9"
    electron-widevinecdm: "^3.0.0"
    firebase: "^4.2.0"
    fs: 0.0.1-security
    grunt-contrib-copy: "^1.0.0"
    jade: "^1.11.0"
    md5: "^2.2.1"
    optional-require: "^1.0.0"
    paper-ripple: "^0.3.0"
    path: "^0.12.7"
    sw-toolbox: "^3.6.0"
    url: "^0.11.0"
    websocket: "^1.0.24"
---
