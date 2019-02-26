---
layout: app

permalink: /ElectronRuler/
description: Ruler made with love and electron.
license: MIT

icons:
  - ElectronRuler/icons/128x128/electron-ruler.png

screenshots:
  - ElectronRuler/screenshot.png

authors:
  - name: Naethaniel
    url: https://github.com/Naethaniel

links:
  - type: GitHub
    url: Naethaniel/electron-ruler
  - type: Download
    url: https://github.com/Naethaniel/electron-ruler/releases

desktop:
  Desktop Entry:
    Name: ElectronRuler
    Comment: Ruler made with love and electron.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: electron-ruler
    StartupWMClass: ElectronRuler
    X-AppImage-Version: 0.0.3
    Categories: Development
    X-AppImage-BuildId: 1HcZdfc6G3aEYa3RHbzskN9Vob9
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: Ruler made with love and electron.
  lint-staged:
    "*.{js,jsx}":
    - cross-env NODE_ENV=development eslint --cache --format=pretty
    - prettier --ignore-path .eslintignore --single-quote --write
    - git add
    "{*.json,.{babelrc,eslintrc,prettierrc,stylelintrc}}":
    - prettier --ignore-path .eslintignore --parser json --write
    - git add
    "*.{css,scss}":
    - stylelint --ignore-path .eslintignore --syntax scss --fix
    - prettier --ignore-path .eslintignore --single-quote --write
    - git add
    "*.{yml,md}":
    - prettier --ignore-path .eslintignore --single-quote --write
    - git add
  main: "./app/main.prod.js"
  repository:
    type: git
    url: git+https://github.com/Naethaniel/electron-ruler.git
  author:
    name: Naethaniel
    url: https://github.com/Naethaniel/electron-ruler
    email: bljuuzeff@gmail.com
  license: MIT
  bugs:
    url: https://github.com/electron-react-boilerplate/electron-react-boilerplate/issues
  jest:
    testURL: http://localhost/
    moduleNameMapper:
      "\\.(jpg|jpeg|png|gif|eot|otf|webp|svg|ttf|woff|woff2|mp4|webm|wav|mp3|m4a|aac|oga)$": "<rootDir>/internals/mocks/fileMock.js"
      "\\.(css|less|sass|scss)$": identity-obj-proxy
    moduleFileExtensions:
    - js
    - jsx
    - json
    transform:
      "^.+\\.jsx?$": babel-jest
    setupFiles:
    - "./internals/scripts/CheckBuiltsExist.js"
  dependencies:
    "@fortawesome/fontawesome-free": "^5.5.0"
    devtron: "^1.4.0"
    electron-debug: "^2.0.0"
    electron-log: "^2.2.17"
    electron-updater: "^3.2.3"
    history: "^4.7.2"
    react: "^16.6.3"
    react-dom: "^16.6.3"
    react-hot-loader: "^4.3.12"
    react-redux: "^5.1.1"
    react-router: "^4.3.1"
    react-router-dom: "^4.3.1"
    redux: "^4.0.1"
    redux-thunk: "^2.3.0"
    source-map-support: "^0.5.9"
  devEngines:
    node: ">=7.x"
    npm: ">=4.x"
    yarn: ">=0.21.3"
---
