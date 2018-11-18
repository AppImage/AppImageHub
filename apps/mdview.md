---
layout: app

permalink: /mdview/
description: Standalone Markdown viewer

icons:
  - mdview/icons/128x128/mdview.png

screenshots:
  - mdview/screenshot.png

authors:
  - name: c3er
    url: https://github.com/c3er

links:
  - type: GitHub
    url: c3er/mdview
  - type: Download
    url: https://github.com/c3er/mdview/releases

desktop:
  Desktop Entry:
    Name: mdview
    Comment: Standalone Markdown viewer
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: mdview
    StartupWMClass: mdview
    X-AppImage-Version: 1.1.2
    Categories: Utility
    X-AppImage-BuildId: 1CBnU77nNgpUnMKNGWB1jgUKJKz
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  repository:
    type: git
    url: https://github.com/c3er/mdview.git
  author: Christian Dreier
  license: MIT
  main: main.js
  dependencies:
    github-markdown-css: "~2.10.0"
    highlight.js: "~9.12.0"
    markdown-it: "~8.4.1"
    markdown-it-headinganchor: "~1.3.0"
---
