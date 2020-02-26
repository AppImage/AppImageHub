---
layout: app

permalink: /UpStream/
description: Streamflow calc utility for Trout Unlimited
license: MIT

icons:
  - UpStream/icons/128x128/upstream.png

screenshots:
  - UpStream/screenshot.png

authors:
  - name: mijdavis2
    url: https://github.com/mijdavis2

links:
  - type: GitHub
    url: mijdavis2/upstream
  - type: Download
    url: https://github.com/mijdavis2/upstream/releases

desktop:
  Desktop Entry:
    Name: UpStream
    Comment: Streamflow calc utility for Trout Unlimited
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: upstream
    X-AppImage-Version: 2.5.4
    X-AppImage-BuildId: 2218a850-9796-11a8-09ce-67adf8d9a82d
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: Streamflow calc utility for Trout Unlimited
  license: MIT
  engines:
    node: 8.2.1
    npm: ">=5.3.0"
  engineStrict: true
  main: "./dist/electron/main.js"
  dependencies:
    ajv: "^5.2.2"
    axios: "^0.16.1"
    fs: "^0.0.1-security"
    lodash.debounce: "^4.0.8"
    moment: "^2.18.1"
    node-async-loop: "^1.2.2"
    primer-css: "^8.0.0"
    vue: 2.4.2
    vue-electron: 1.0.6
    vue-floatthead: 0.0.5
    vue-router: 2.7.0
    vue-scrollto: 2.7.2
    vue-sweetalert: "^0.1.18"
    vue2-scrollspy: 1.1.2
    vuex: 2.3.1
---
