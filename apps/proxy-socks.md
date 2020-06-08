---
layout: app

permalink: /proxy-socks/
description: Electron app containing SOCKSv5 server and SSH2 client
license: MIT

icons:
  - proxy-socks/icons/512x512/proxy-socks.png

screenshots:
  - proxy-socks/screenshot.png

authors:
  - name: ab77
    url: https://github.com/ab77

links:
  - type: GitHub
    url: ab77/proxy-socks
  - type: Download
    url: https://github.com/ab77/proxy-socks/releases

desktop:
  Desktop Entry:
    Name: proxy-socks
    Comment: Electron app containing SOCKSv5 server and SSH2 client
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: proxy-socks
    X-AppImage-Version: 1.0.4
    X-AppImage-BuildId: db954070-8fbe-11a8-10d5-dfe78f016485
    Categories: Network
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: Electron app containing SOCKSv5 server and SSH2 client
  author:
    name: belodetek.io
    email: team@belodetek.io
    url: http://belodetek.io
  repository: https://github.com/ab77/proxy-socks
  main: main.js
  dependencies:
    socksv5: git://github.com/mscdex/socksv5.git
    ssh2: git://github.com/mscdex/ssh2.git
    string.format: "*"
    auto-launch: "*"
    update-electron-app: "*"
---
