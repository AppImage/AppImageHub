---
layout: app

permalink: /Stargazer/
description: Network discovery and product administration toolset for holographic displays

icons:
  - Stargazer/icons/128x128/stargazer.png

screenshots:
  - Stargazer/screenshot.png

authors:
  - name: Holusion
    url: https://github.com/Holusion

links:
  - type: GitHub
    url: Holusion/stargazer
  - type: Download
    url: https://github.com/Holusion/stargazer/releases

desktop:
  Desktop Entry:
    Name: holusion-stargazer
    Comment: Network discovery and product administration toolset for holographic displays
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: stargazer
    X-AppImage-Version: 1.1.1.41
    X-AppImage-BuildId: 98d042e0-b1e6-11a8-0e5c-33adef033768
    Categories: Network
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
    displays
  main: main.js
  homepage: https://github.com/Holusion/stargazer/releases/latest
  author: Sebastien DUMETZ <s.dumetz@holusion.com>
  license: MIT
  dependencies:
    bonjour: "^3.5.0"
    electron-dl: "^1.12.0"
    express: "^4.16.3"
    form-data: "^2.3.2"
    http-proxy: "^1.16.2"
    material-components-web: "^0.32.0"
    mdns: "^2.3.4"
    nan: "^2.9.2"
    navigo: "^7.1.1"
    request: "^2.88.0"
    socketio: "^1.0.0"
    winston: "^2.4.1"
  optionalDependencies:
    wixtoolset-compiler: "^1.0.3"
---
