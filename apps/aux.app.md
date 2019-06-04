---
layout: app

permalink: /aux.app/
description: Native aux.app player to play music from YouTube, SoundCloud, MixCloud, Deezer,...

icons:
  - aux.app/icons/1024x1024/aux-app-native.png

screenshots:
  - aux.app/screenshot.png

authors:
  - name: auxdotapp
    url: https://github.com/auxdotapp

links:
  - type: GitHub
    url: auxdotapp/desktop-app
  - type: Download
    url: https://github.com/auxdotapp/desktop-app/releases

desktop:
  Desktop Entry:
    Name: aux-app
    Comment: Native aux.app player to play music from YouTube, SoundCloud, MixCloud,
      Deezer,...
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: aux-app-native
    StartupWMClass: aux-app
    X-AppImage-Version: 2.0.1.10
    Categories: Utility
    X-AppImage-BuildId: 1FGJHk2r36xJYpubyCKAASvx90S
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
    Deezer,...
  main: "./src/main.js"
  private: true
  author: aux.app development team
  licenses:
  - type: MIT
    url: http://www.opensource.org/licenses/mit-license.php
  dependencies:
    backbone: 1.2.3
    lokijs: 1.5.5
    underscore: 1.8.3
    q: 1.5.1
  repository:
    type: git
    url: https://github.com/auxdotapp/desktop-app.git
  bugs:
    url: https://github.com/auxdotapp/desktop-app/issues
  homepage: https://aux.app
---
