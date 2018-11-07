---
layout: app

permalink: /borderless-camera/
description: a simple camera app without window borders, useful for the screencast recording

icons:
  - borderless-camera/icons/128x128/borderless-camera.png

screenshots:
  - borderless-camera/screenshot.png

authors:
  - name: grigio
    url: https://github.com/grigio

links:
  - type: GitHub
    url: grigio/borderless-camera
  - type: Download
    url: https://github.com/grigio/borderless-camera/releases

desktop:
  Desktop Entry:
    Name: borderless-camera
    Comment: a simple camera app without window borders, useful for the screencast recording
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: borderless-camera
    StartupWMClass: borderless-camera
    X-AppImage-Version: 0.0.5
    Categories: Development
    X-AppImage-BuildId: 1B4RJ1LUJR9ho3KayhysMx8T0FB
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  version: 0.0.5
  license: MIT
  author:
    name: Luigi Maselli
    email: grigio.org@gmail.com
    url: https://grigio.org
  private: true
  main: src/index.js
---
