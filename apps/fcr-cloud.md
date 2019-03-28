---
layout: app

permalink: /fcr-cloud/
description: Ein Web-Desktop-Client für Faschingsclub Rain e.V. - Cloud
license: GPL-3.0

icons:
  - fcr-cloud/icons/128x128/fcr-cloud.png

screenshots:
  - fcr-cloud/screenshot.png

authors:
  - name: BunsiMedia
    url: https://github.com/BunsiMedia

links:
  - type: GitHub
    url: BunsiMedia/fcr-cloud
  - type: Download
    url: https://github.com/BunsiMedia/fcr-cloud/releases

desktop:
  Desktop Entry:
    Name: Faschingsclub Rain e.V. Cloud
    Comment: Ein Web-Desktop-Client für Faschingsclub Rain e.V. - Cloud
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: fcr-cloud
    StartupWMClass: Faschingsclub Rain e.V. Cloud
    X-AppImage-Version: 1.0.4
    Categories: Network
    X-AppImage-BuildId: 1IaXhLsjiNVhGbsxY8OPeobb2dR
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  description: Ein Web-Desktop-Client für Faschingsclub Rain e.V. - Cloud
  main: src/main.js
  author: BunsiMedia
  license: GPL-3.0
  homepage: https://cloud.faschingsclubrain.de
---
