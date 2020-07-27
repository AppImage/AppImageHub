---
layout: app

permalink: /jupyterlab/
description: A native app for JupyterLab, based on electron.
license: BSD-3-Clause

screenshots:
  - jupyterlab/screenshot.png

authors:
  - name: jupyterlab
    url: https://github.com/jupyterlab

links:
  - type: GitHub
    url: jupyterlab/jupyterlab_app
  - type: Download
    url: https://github.com/jupyterlab/jupyterlab_app/releases

desktop:
  Desktop Entry:
    Name: JupyterLab
    Comment: A native app for JupyterLab, based on electron.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: jupyterlab_app
    X-AppImage-Version: 0.2.0
    X-AppImage-BuildId: 8bf4f620-5a15-11a8-3744-51e69267f20a
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: BSD-3-Clause

electron:
  main: "./build/out/main/main.js"
  author:
    name: Project Jupyter
    email: project.jupyter@gmail.com
    url: http://jupyter.org
  homepage: https://github.com/jupyterlab/jupyterlab_app#readme
  repository: github:jupyterlab/jupyterlab
  license: BSD-3-Clause
  dependencies:
    "@jupyterlab/application": "^0.15.4"
    "@jupyterlab/application-extension": "^0.15.4"
    "@jupyterlab/apputils": "^0.15.5"
    "@jupyterlab/apputils-extension": "^0.15.4"
    "@jupyterlab/cells": "^0.15.4"
    "@jupyterlab/codeeditor": "^0.15.4"
    "@jupyterlab/codemirror": "^0.15.4"
    "@jupyterlab/codemirror-extension": "^0.15.4"
    "@jupyterlab/completer": "^0.15.4"
    "@jupyterlab/completer-extension": "^0.15.4"
    "@jupyterlab/console": "^0.15.4"
    "@jupyterlab/console-extension": "^0.15.4"
    "@jupyterlab/coreutils": "^1.0.9"
    "@jupyterlab/csvviewer": "^0.15.4"
    "@jupyterlab/csvviewer-extension": "^0.15.4"
    "@jupyterlab/docmanager": "^0.15.5"
    "@jupyterlab/docmanager-extension": "^0.15.4"
    "@jupyterlab/docregistry": "^0.15.5"
    "@jupyterlab/faq-extension": "^0.15.5"
    "@jupyterlab/filebrowser": "^0.15.4"
    "@jupyterlab/filebrowser-extension": "^0.15.5"
    "@jupyterlab/fileeditor": "^0.15.4"
    "@jupyterlab/fileeditor-extension": "^0.15.4"
    "@jupyterlab/help-extension": "^0.15.4"
    "@jupyterlab/imageviewer": "^0.15.4"
    "@jupyterlab/imageviewer-extension": "^0.15.4"
    "@jupyterlab/inspector": "^0.15.4"
    "@jupyterlab/inspector-extension": "^0.15.4"
    "@jupyterlab/json-extension": "^0.15.4"
    "@jupyterlab/launcher": "^0.15.4"
    "@jupyterlab/launcher-extension": "^0.15.4"
    "@jupyterlab/mainmenu": "^0.4.4"
    "@jupyterlab/mainmenu-extension": "^0.4.5"
    "@jupyterlab/markdownviewer-extension": "^0.15.4"
    "@jupyterlab/mathjax2-extension": "^0.3.4"
    "@jupyterlab/notebook": "^0.15.6"
    "@jupyterlab/notebook-extension": "^0.15.4"
    "@jupyterlab/observables": "^1.0.6"
    "@jupyterlab/outputarea": "^0.15.5"
    "@jupyterlab/pdf-extension": "^0.7.4"
    "@jupyterlab/rendermime": "^0.15.4"
    "@jupyterlab/rendermime-extension": "^0.9.4"
    "@jupyterlab/rendermime-interfaces": "^1.0.6"
    "@jupyterlab/running": "^0.15.4"
    "@jupyterlab/running-extension": "^0.15.4"
    "@jupyterlab/services": "^1.1.4"
    "@jupyterlab/settingeditor": "^0.4.4"
    "@jupyterlab/settingeditor-extension": "^0.10.4"
    "@jupyterlab/shortcuts-extension": "^0.15.4"
    "@jupyterlab/tabmanager-extension": "^0.15.4"
    "@jupyterlab/terminal": "^0.15.4"
    "@jupyterlab/terminal-extension": "^0.15.4"
    "@jupyterlab/theme-dark-extension": "^0.15.4"
    "@jupyterlab/theme-light-extension": "^0.15.4"
    "@jupyterlab/tooltip": "^0.15.4"
    "@jupyterlab/tooltip-extension": "^0.15.4"
    "@jupyterlab/vdom-extension": "^0.15.4"
    "@jupyterlab/vega2-extension": "^0.15.5"
    "@types/node": "^9.4.6"
    "@types/react": "~16.0.19"
    "@types/react-dom": "^16.0.4"
    "@types/semver": "^5.4.0"
    "@types/yargs": "^11.0.0"
    bottlejs: "^1.6.1"
    electron-debug: "^1.2.0"
    electron-log: "^2.2.14"
    es6-promise: "^4.1.1"
    fix-path: "^2.1.0"
    font-awesome: "^4.7.0"
    jshint: "^2.9.5"
    react: "~16.2.0"
    react-dom: "~16.2.0"
    semver: "^5.4.1"
    which: "^1.3.0"
    winreg: "^1.2.4"
    xterm: "^3.0.2"
    yargs: "^11.0.0"
  resolutions:
    "@types/react-dom/@types/react": "~16.0.19"
---
