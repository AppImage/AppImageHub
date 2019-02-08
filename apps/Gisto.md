---
layout: app

permalink: /Gisto/
description: Gisto is a Cross-platform snippets management desktop application that allows you and/or your team share code snippets fast and easily. Based on GitHub Gists Infrastructure which means you can use all your existing snippets by connecting your GitHub account! Gisto started as an attempt to fulfill the lack of a syntax highlighted and cloud synchronized code snippet solution. You may think of Gisto as Evernote for code.
license: MIT

icons:
  - Gisto/icons/512x512/gisto.png

screenshots:
  - Gisto/screenshot.png

authors:
  - name: Gisto
    url: https://github.com/Gisto

links:
  - type: GitHub
    url: Gisto/Gisto
  - type: Download
    url: https://github.com/Gisto/Gisto/releases

desktop:
  Desktop Entry:
    Name: Gisto
    Comment: Gisto is a Cross-platform snippets management desktop application that
      allows you and/or your team share code snippets fast and easily. Based on GitHub
      Gists Infrastructure which means you can use all your existing snippets by connecting
      your GitHub account! Gisto started as an attempt to fulfill the lack of a syntax
      highlighted and cloud synchronized code snippet solution. You may think of Gisto
      as Evernote for code.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: gisto
    StartupWMClass: Gisto
    X-AppImage-Version: 1.9.69.422
    Categories: Development
    X-AppImage-BuildId: 190M1cGVbufTD6V6Z92K1jBTej0
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
    allows you and/or your team share code snippets fast and easily. Based on GitHub
    Gists Infrastructure which means you can use all your existing snippets by connecting
    your GitHub account! Gisto started as an attempt to fulfill the lack of a syntax
    highlighted and cloud synchronized code snippet solution. You may think of Gisto
    as Evernote for code.
  productName: Gisto
  main: main.js
  repository:
    type: git
    url: https://github.com/gisto/gisto.git
  bugs:
    url: https://github.com/gisto/gisto/issues
  homepage: http://www.gistoapp.com/
  authors:
  - name: Maayan Glikser
    url: http://www.glikm.com
  - name: Sasha Khamkov
    url: http://www.sanusart.com
  license: MIT
  readmeFilename: README.md
  dependencies:
    "@sentry/electron": "^0.7.0"
    dotenv: "^6.0.0"
    electron-config: "^1.0.0"
    electron-log: "^2.2.15"
    electron-settings: "^3.2.0"
    electron-store: "^2.0.0"
    electron-updater: "^3.0.3"
    github-markdown-css: "^2.10.0"
    highlight.js: "^9.12.0"
    lodash: "^4.17.10"
    marked: "^0.4.0"
    monaco-editor: "^0.13.1"
    mousetrap: "^1.6.2"
    normalize.css: "^8.0.0"
    polished: "^1.9.3"
    react: "^16.3.2"
    react-dom: "^16.3.2"
    react-emotion: "^9.1.3"
    react-monaco-editor: "^0.17.2"
    react-redux: "^5.0.7"
    react-router-dom: "^4.2.2"
    react-router-redux: "^5.0.0-alpha.9"
    redux: "^4.0.0"
    reselect: "^3.0.1"
    semver: "^5.5.0"
    styled-components: "^3.2.6"
    superagent: "^3.8.3"
    wait-on: "^2.1.0"
  husky:
    hooks:
      pre-commit: npm run lint && npm test
---
