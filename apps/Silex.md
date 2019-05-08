---
layout: app

permalink: /Silex/
description: Free and easy website builder for everyone.
license: GPL-3.0

icons:
  - Silex/icons/128x128/silex.png

screenshots:
  - Silex/screenshot.png

authors:
  - name: silexlabs
    url: https://github.com/silexlabs

links:
  - type: GitHub
    url: silexlabs/Silex
  - type: Download
    url: https://github.com/silexlabs/Silex/releases

desktop:
  Desktop Entry:
    Name: silex
    Comment: Free and easy website builder for everyone.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: silex
    StartupWMClass: silex
    X-AppImage-Version: 2.4.0.376
    Categories: Network
    X-AppImage-BuildId: 1GYKHUdnicDH2AQYG69JpNhIKmI
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  version:frontend: '2.8'
  version:backwardcompat: 2.2.8
  author: Alex Hoyau <a.hoyau@silexlabs.org> (https://lexoyo.me/)
  main: dist/server/index.js
  license: GPL-3.0
  engines:
    node: 8.10.x
    npm: 5.6.x
  precommit:
  - lint:js
  - lint:server
  dependencies:
    bluebird: 3.5.1
    body-parser: "^1.18.2"
    cloud-explorer: github:silexlabs/CloudExplorer2#master
    compression: 1.7.2
    cookie-parser: 1.4.3
    cookie-session: 2.0.0-beta.3
    cross-env: 5.1.4
    express: 4.16.3
    express-force-ssl: 0.3.2
    google-closure-compiler: 20170218.0.0
    google-closure-library: 20170218.0.1
    jade: 1.11.0
    jsdom: 11.6.2
    less: 3.0.1
    node_modules-path: github:lexoyo/node_modules-path#master
    prodotype: github:silexlabs/Prodotype#master
    promise-sequential: 1.1.1
    request: 2.85.0
    serve-static: 1.13.2
    silex-blank-templates: github:silexlabs/silex-blank-templates#ccc0c2292ba609dadd89b43710f0a1ed1c9c7cdd
    silex-templates: github:silexlabs/silex-templates#ed1a0e4e9e46340d6785e97a9fcca21db3077626
    wysihtml: "^0.6.0-beta1"
  repository:
    type: git
    url: https://github.com/silexlabs/Silex.git
---
