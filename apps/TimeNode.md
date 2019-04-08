---
layout: app

permalink: /TimeNode/
license: MIT

icons:
  - TimeNode/icons/256x256/eth-alarm-clock-dapp.png

screenshots:
  - TimeNode/screenshot.png

authors:
  - name: chronologic
    url: https://github.com/chronologic

links:
  - type: GitHub
    url: chronologic/eth-alarm-clock-dapp
  - type: Download
    url: https://github.com/chronologic/eth-alarm-clock-dapp/releases

desktop:
  Desktop Entry:
    Name: TimeNode
    Comment: 
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: eth-alarm-clock-dapp
    StartupWMClass: TimeNode
    X-AppImage-Version: 1.4.2
    Categories: Finance
    X-AppImage-BuildId: 1HEVHXDpQHKOSbTtpe2jRqHaN3z
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: ''
  lint-staged:
    "*.js":
    - eslint --fix
    - prettier --write --config ./.prettierrc --config-precedence file-override
    - git add
  dependencies:
    electron-is-dev: 1.0.1
    electron-updater: 4.0.6
  repository:
    type: git
    url: https://github.com/chronologic/eth-alarm-clock-dapp
  browserslist:
  - defaults
  - not ie < 11
  jest:
    modulePathIgnorePatterns:
    - "<rootDir>/eth-alarm-clock-dapp-.*"
    testURL: http://localhost
  license: MIT
  husky:
    hooks:
      pre-commit: lint-staged
---
