---
layout: app

permalink: /Sirius_Tracker/
description: Sirius Tracker for Linux
license: MIT

icons:
  - Sirius_Tracker/icons/128x128/sirius-tracker.png

screenshots:
  - Sirius_Tracker/screenshot.png

authors:
  - name: demartini
    url: https://github.com/demartini

links:
  - type: GitHub
    url: demartini/sirius-tracker
  - type: Download
    url: https://github.com/demartini/sirius-tracker/releases

desktop:
  Desktop Entry:
    Name: Sirius Tracker
    Comment: Sirius Tracker for Linux
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: sirius-tracker
    StartupWMClass: Sirius Tracker
    X-AppImage-Version: 1.2.0.39
    Categories: GNOME
    X-AppImage-BuildId: 1JwfCXSrbzum4yvbTbQeFu5Ql4l
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: A app for track Sirius market information.
  main: "./src/app.js"
  license: MIT
  copyright: Iolar Demartini Junior
  author:
    name: Iolar Demartini Junior
    email: iolardemartini@gmail.com
    url: https://iolardemartini.com
  homepage: https://github.com/demartini/sirius-tracker#readme
  repository:
    type: git
    url: https://github.com/demartini/sirius-tracker.git
  bugs:
    url: https://github.com/demartini/sirius-tracker/issues
  postinstall: electron-builder install-app-deps
  dependencies:
    "@amaurymartiny/menubar": "^6.0.0"
    "@fortawesome/fontawesome-free": "^5.8.1"
    auto-launch: "^5.0.5"
    bootstrap: "^4.3.1"
    electron-is-dev: "^1.1.0"
    electron-log: "^3.0.5"
    electron-store: "^3.2.0"
    electron-updater: "^4.0.6"
    jquery: "^3.4.0"
    numeral: "^2.0.6"
    popper.js: "^1.15.0"
  husky:
    hooks:
      pre-commit: lint-staged
  lint-staged:
    "*.js":
    - prettier --write
    - eslint
    - git add
    "*.css":
    - stylelint --fix
    - git add
    "*.html":
    - prettier --write
    - git add
---
