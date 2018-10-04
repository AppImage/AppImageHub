---
layout: app

permalink: /SystemDelight/
description: Process and systemd manager for Linux environments
license: GPL-3.0

icons:
  - SystemDelight/icons/128x128/system-delight.png

screenshots:
  - SystemDelight/screenshot.png

authors:
  - name: jaszhix
    url: https://github.com/jaszhix

links:
  - type: GitHub
    url: jaszhix/SystemDelight
  - type: Download
    url: https://github.com/jaszhix/SystemDelight/releases

desktop:
  Desktop Entry:
    Name: SystemDelight
    Comment: Process and systemd manager for Linux environments
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: system-delight
    StartupWMClass: SystemDelight
    X-AppImage-Version: 0.0.2
    Categories: Development
    X-AppImage-BuildId: 1B4tFLh7TbpLnN7wvafHH2jDUqE
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

electron:
  description: Process and systemd manager for Linux environments
  main: "./main.prod.js"
  author:
    name: Jason Hicks
    email: jaszhix@gmail.com
    url: https://github.com/jaszhix
  license: GPL-3.0-or-later
  dependencies: {}
---
