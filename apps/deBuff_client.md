---
layout: app

permalink: /deBuff_client/
description: A client used to distribute a website’s content via WebTorrent.

icons:
  - deBuff_client/icons/128x128/debuff-client.png

screenshots:
  - deBuff_client/screenshot.png

authors:
  - name: BraedenDiaz
    url: https://github.com/BraedenDiaz

links:
  - type: GitHub
    url: BraedenDiaz/debuff_client
  - type: Download
    url: https://github.com/BraedenDiaz/debuff_client/releases

desktop:
  Desktop Entry:
    Name: deBuff Client
    Comment: A client used to distribute a website’s content via WebTorrent.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: debuff-client
    StartupWMClass: deBuff Client
    X-AppImage-Version: 1.0.1
    Categories: Network
    X-AppImage-BuildId: 1K21cqjbHovSIIE812DM6erfCg9
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: "./controllers/main.js"
  author: Braeden Diaz <braedendiaz@gmail.com>
  homepage: https://debuff.info
  license: MIT
  dependencies:
    electron-log: "^3.0.5"
    electron-updater: "^4.0.6"
    jquery: "^3.3.1"
    rimraf: "^2.6.3"
    vis: "^4.21.0"
    webtorrent: "^0.103.0"
    ws: "^6.1.2"
---
