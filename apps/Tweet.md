---
layout: app

permalink: /Tweet/
description: Desktop app only for tweeting. Timeline never shows up
license: MIT

icons:
  - Tweet/icons/512x512/tweet-app.png

screenshots:
  - Tweet/screenshot.png

authors:
  - name: rhysd
    url: https://github.com/rhysd

links:
  - type: GitHub
    url: rhysd/tweet-app
  - type: Download
    url: https://github.com/rhysd/tweet-app/releases

desktop:
  Desktop Entry:
    Name: Tweet
    Comment: Desktop app only for tweeting. Timeline never shows up
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: tweet-app
    StartupWMClass: Tweet
    X-AppImage-Version: 0.1.0
    Categories: Network
    X-AppImage-BuildId: 1HiXETN94FUszrLXoBEqL4Om8wf
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT
---
