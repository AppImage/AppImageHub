---
layout: app

permalink: /Unity_Hub/
description: The Official Unity Hub

icons:
  - Unity_Hub/icons/48x48/unityhub.png

screenshots:
  - Unity_Hub/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: Unity Hub
    Comment: The Official Unity Hub
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: unityhub
    X-AppImage-Version: 1.2.0
    X-AppImage-BuildId: 32fb5090-d87e-11a8-0ba0-31e85e81896d
    MimeType: x-scheme-handler/unityhub
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  main: index.js
  repository:
    type: git
    url: https://gitlab.internal.unity3d.com/hub/uw-hub
  author: Unity Technologies Inc.
  license: CC0-1.0
  bugs:
    url: https://github.com/electron/electron-quick-start/issues
  homepage: https://github.com/electron/electron-quick-start#readme
  dependencies:
    "@unityhub/hub-generate-releases": "^1.1.6"
    arch: "^2.1.0"
    connect: "^3.3.5"
    diskusage: "^0.2.4"
    electron-debug: "^1.0.1"
    electron-is-dev: "^0.1.2"
    electron-json-storage: "^2.1.0"
    electron-settings: "^3.2.0"
    electron-updater: 3.0.3
    es6-promisify: "^5.0.0"
    fs-extra: "^4.0.0"
    iso-3166-2: https://github.com/olahol/iso-3166-2.js#c2a41d682e824a1905f70dc04a4cff89e04e883d
    jquery: "^2.1.4"
    js-yaml: "^3.6.1"
    lodash: "^4.17.10"
    machina: "^2.0.2"
    machina.postal: "^0.4.0"
    md5: "^2.2.1"
    md5-file: "^3.2.3"
    node-ipc: "^9.1.1"
    numeral: "^2.0.6"
    postal: "^2.0.4"
    ps-node: "^0.1.6"
    recursive-readdir: git://github.com/UnityTech/recursive-readdir/
    remote-file-size: "^3.0.4"
    request: "^2.88.0"
    request-progress: "^3.0.0"
    request-promise-native: "^1.0.5"
    require-all: "^2.0.0"
    rimraf: "^2.6.2"
    sax: "^1.2.4"
    simple-plist: "^0.3.0"
    sudo-prompt: "^7.1.0"
    swagger-connect: "^0.1.0"
    tar: 4.4.6
    unity-editor-home: https://www.myget.org/F/unity-editor-home_dev/npm/unity-editor-home/-/unity-editor-home-0.30.0.tgz
    unity-editor-license: https://www.myget.org/F/unity-editor-home_dev/npm/unity-editor-license/-/unity-editor-license-1.0.6.tgz
    universal-analytics: "^0.3.11"
    uuid: "^3.3.2"
    winston: "^2.4.3"
    ws: "^1.1.1"
    xml-crypto: git://github.com/UnityTech/xml-crypto/
    xml2js: "^0.4.19"
    xmldom: "^0.1.27"
    yargs: "^4.6.0"
    yauzl: "^2.10.0"
    yazl: "^2.4.3"
  optionalDependencies:
    dmg: "^0.1.0"
    fs-ext: "^1.2.1"
    is-admin: "^2.1.1"
    node-osascript: "^2.0.0"
    unity-editor-registry: https://www.myget.org/F/unity-editor-home_dev/npm/unity-editor-registry/-/unity-editor-registry-1.0.2.tgz
    unity-editor-version: https://www.myget.org/F/unity-editor-home_dev/npm/unity-editor-version/-/unity-editor-version-1.0.2.tgz
    windows-registry: "^0.1.3"
    windows-shortcuts: "^0.1.6"
  standard:
    ignore:
    - Unity Hub.app/**
    - "**/node_modules/**"
---
