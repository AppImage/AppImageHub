---
layout: app

permalink: /SiriusTracker/
description: SiriusTracker is a app for track Sirius market information.

icons:
  - SiriusTracker/icons/128x128/siriustracker.png

screenshots:
  - SiriusTracker/screenshot.png

authors:
  - name: demartini
    url: https://github.com/demartini

links:
  - type: GitHub
    url: demartini/SiriusTracker
  - type: Download
    url: https://github.com/demartini/SiriusTracker/releases

desktop:
  Desktop Entry:
    Name: SiriusTracker
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: siriustracker
    StartupWMClass: SiriusTracker
    X-AppImage-Version: 0.0.1-beta.1
    Comment: SiriusTracker is a app for track Sirius market information.
    Categories: GNOME
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  version: 0.0.1-beta.1
  description: SiriusTracker is a app for track Sirius market information.
  main: "./src/app.js"
  license: MIT
  copyright: Iolar Demartini Junior
  author:
    name: Iolar Demartini Junior
    email: iolardemartini@gmail.com
    url: https://demartini.dev
  homepage: https://github.com/demartini/SiriusTracker
  repository:
    type: git
    url: https://github.com/demartini/SiriusTracker.git
  bugs:
    url: https://github.com/demartini/SiriusTracker/issues
  postinstall: electron-builder install-app-deps
  dependencies:
    "@fortawesome/fontawesome-free": 5.11.2
    auto-launch: 5.0.5
    bootstrap: 4.3.1
    electron-is-dev: 1.1.0
    electron-log: 3.0.9
    electron-store: 5.1.0
    electron-updater: 4.2.0
    jquery: 3.4.1
    menubar: 7.0.0
    numeral: 2.0.6
    popper.js: 1.16.0
  husky:
    hooks:
      pre-commit: lint-staged
      commit-msg: commitlint -E HUSKY_GIT_PARAMS
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
  config:
    commitizen:
      path: "./node_modules/cz-conventional-changelog"
---
