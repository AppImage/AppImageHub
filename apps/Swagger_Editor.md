---
layout: app

permalink: /Swagger_Editor/
description: Swagger Editor Desktop Edition

screenshots:
  - Swagger_Editor/screenshot.png

authors:
  - name: muhonglong
    url: https://github.com/muhonglong

links:
  - type: GitHub
    url: muhonglong/swagger-editor-desktop
  - type: Download
    url: https://github.com/muhonglong/swagger-editor-desktop/releases

desktop:
  Desktop Entry:
    Name: Swagger Editor
    Comment: Swagger Editor Desktop Edition
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: swagger_editor_desktop
    X-AppImage-Version: 0.0.2
    X-AppImage-BuildId: ac079790-0e63-11a8-3ed7-79b6013cac63
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Swagger Editor Desktop Edition
  main: src/main.js
  repository:
    type: git
    url: git+ssh://git@github.com/muhonglong/swagger-editor-desktop.git
  author: Li Xiao-Bo <xiaoboleee@gmail.com>
  license: Apache-2.0
  homepage: https://github.com/muhonglong/swagger-editor-desktop#readme
  dependencies:
    about-window: "^1.8.0"
    electron-json-storage: "^4.0.2"
    electron-preferences: "^0.0.6"
    js-yaml: "^3.10.0"
    mousetrap: "^1.6.1"
    swagger-editor-dist: "^3.2.8"
---
