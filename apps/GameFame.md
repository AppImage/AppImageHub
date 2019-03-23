---
layout: app

permalink: /GameFame/
description: COMS 4156: Advanced Software Engineering Project
license: MIT

icons:
  - GameFame/icons/128x128/game-fame.png

screenshots:
  - GameFame/screenshot.png

authors:
  - name: alekzieba
    url: https://github.com/alekzieba

links:
  - type: GitHub
    url: alekzieba/game-fame
  - type: Download
    url: https://github.com/alekzieba/game-fame/releases

desktop:
  Desktop Entry:
    Name: GameFame
    Comment: 'COMS 4156: Advanced Software Engineering Project'
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: game-fame
    StartupWMClass: GameFame
    X-AppImage-Version: 0.0.1.68
    Categories: Development
    X-AppImage-BuildId: 1EXeyAA4F19ffUkJu27lztdwGgL
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: 'COMS 4156: Advanced Software Engineering Project'
  main: "./main.prod.js"
  author:
    name: John Doe
    email: johndoe@gmail.com
    url: https://github.com/johndoe
  license: MIT
  dependencies:
    firebase: "^5.5.7"
    grpc: "^1.16.0"
---
