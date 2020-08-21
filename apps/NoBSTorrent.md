---
layout: app

permalink: /NoBSTorrent/
description: An ad-free, no-bullshit torrent client.
license: GPL-3.0

icons:
  - NoBSTorrent/icons/512x512/nobstorrent.png

screenshots:
  - NoBSTorrent/screenshot.png

authors:
  - name: moriczgergo
    url: https://github.com/moriczgergo

links:
  - type: GitHub
    url: moriczgergo/nobstorrent
  - type: Download
    url: https://github.com/moriczgergo/nobstorrent/releases

desktop:
  Desktop Entry:
    Name: nobstorrent
    Comment: An ad-free, no-bullshit torrent client.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: nobstorrent
    StartupWMClass: nobstorrent
    X-AppImage-Version: 1.0.0.14
    Categories: Utility
    X-AppImage-BuildId: 1G2RBs3Vqxrc32h7uLxdooc7PDa
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  main: main.js
  repository: https://github.com/electron/electron-quick-start
  author: skiilaa
  license: GPL-3.0
  dependencies:
    electron-is-dev: "^1.0.1"
    webtorrent: "^0.103.0"
---
