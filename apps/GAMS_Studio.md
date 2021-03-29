---
layout: app

permalink: /GAMS_Studio/
license: GPL-3.0

icons:
  - GAMS_Studio/icons/scalable/gamslogo.svg

screenshots:
  - GAMS_Studio/screenshot.png

authors:
  - name: GAMS-dev
    url: https://github.com/GAMS-dev

links:
  - type: GitHub
    url: GAMS-dev/studio
  - type: Download
    url: https://github.com/GAMS-dev/studio/releases

desktop:
  Desktop Entry:
    Type: Application
    Name: GAMS Studio
    TryExec: studio
    Exec: studio %F
    Icon: gamslogo
    Terminal: false
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0
---
