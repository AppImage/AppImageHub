---
layout: app

permalink: /RoloViewer/
description: Image slideshow viewer

icons:
  - RoloViewer/icons/256x256/roloviewer.png

screenshots:
  - RoloViewer/screenshot.png

authors:
  - name: rosenloecher-it
    url: https://github.com/rosenloecher-it

links:
  - type: GitHub
    url: rosenloecher-it/roloviewer
  - type: Download
    url: https://github.com/rosenloecher-it/roloviewer/releases

desktop:
  Desktop Entry:
    Name: RoloViewer
    Comment: Image slideshow viewer
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: roloviewer
    StartupWMClass: RoloViewer
    X-AppImage-Version: 0.7.1
    Categories: Graphics
    X-AppImage-BuildId: 1BVz9DReRDzVm9Nb8LTewZVHAF6
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Image slideshow viewer
  main: "./dist/main.prod.js"
  author:
    name: Raul Rosenlöcher
    email: roloviewer@rosenloecher-it.de
    url: https://www.rosenloecher-it/roloviewer/
  license: MIT
  dependencies:
    exiftool-vendored: "^5.5.0"
---
