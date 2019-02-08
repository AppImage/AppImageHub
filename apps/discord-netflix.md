---
layout: app

permalink: /discord-netflix/
description: A Netflix wrapper with Discord Rich Presence

icons:
  - discord-netflix/icons/512x512/netflix.png

screenshots:
  - discord-netflix/screenshot.png

authors:
  - name: nirewen
    url: https://github.com/nirewen

links:
  - type: GitHub
    url: nirewen/discord-netflix
  - type: Download
    url: https://github.com/nirewen/discord-netflix/releases

desktop:
  Desktop Entry:
    Name: Netflix
    Comment: A Netflix wrapper with Discord Rich Presence
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: netflix
    X-AppImage-Version: 2.0.1.2
    X-AppImage-BuildId: 823aa200-0c6d-11a9-05d0-a1d054cc731f
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: src/index.js
  repository:
    type: git
    url: git+ssh://git@github.com/nirewen/discord-netflix.git
  author: Nirewen
  license: ISC
  homepage: https://github.com/nirewen/discord-netflix#readme
  dependencies:
    discord-rpc: "^3.0.1"
    electron-widevinecdm: "^5.0.2"
    moment: "^2.22.2"
---
