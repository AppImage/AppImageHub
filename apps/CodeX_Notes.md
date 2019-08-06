---
layout: app

permalink: /CodeX_Notes/
description: Simple, fast and useful crossplatform notes application based on CodeX Editor and Electron.

icons:
  - CodeX_Notes/icons/1024x1024/codex.notes.png

screenshots:
  - CodeX_Notes/screenshot.png

authors:
  - name: codex-team
    url: https://github.com/codex-team

links:
  - type: GitHub
    url: codex-team/codex.notes
  - type: Download
    url: https://github.com/codex-team/codex.notes/releases

desktop:
  Desktop Entry:
    Name: CodeX Notes
    Comment: Simple, fast and useful crossplatform notes application based on CodeX
      Editor and Electron.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: codex.notes
    X-AppImage-Version: 2.2.2
    X-AppImage-BuildId: 39aa5250-136c-11a9-0c50-b55adbb29a62
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Simple, fast and useful crossplatform notes application based on CodeX
    Editor and Electron.
  main: "./src/codex-notes.js"
  author:
    name: CodeX
    email: team@ifmo.su
  license: MIT
  homepage: https://ifmo.su/notes
  repository:
    url: https://github.com/codex-team/codex.notes
  bugs: https://github.com/codex-team/codex.notes/issues/new
  dependencies:
    "@codexteam/hawk.nodejs": "^1.2.1"
    "@codexteam/shortcuts": "^1.0.0"
    electron-oauth2: "^3.0.0"
    electron-pug: "^1.5.1"
    electron-updater: "^2.21.11"
    graphql-request: "^1.5.1"
    is-online: "^7.0.0"
    nedb: "^1.8.0"
    node-machine-id: "^1.1.10"
    node-notifier: "^5.2.1"
    request: "^2.85.0"
    request-promise: "^4.2.2"
    sanitize-html: "^1.18.2"
    tapable: "^1.0.0"
    winston: "^3.0.0-rc4"
    winston-daily-rotate-file: "^3.1.2"
    ws: "^5.1.0"
  optionalDependencies: {}
---
