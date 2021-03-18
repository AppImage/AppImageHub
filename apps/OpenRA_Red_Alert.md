---
layout: app

permalink: /OpenRA_Red_Alert/
description: Reimagining of early Westwood Games
license: GPL-3.0

icons:
  - OpenRA_Red_Alert/icons/128x128/openra-d2k.png

screenshots:
  - OpenRA_Red_Alert/screenshot.png

authors:
  - name: OpenRA
    url: https://github.com/OpenRA

links:
  - type: GitHub
    url: OpenRA/OpenRA
  - type: Download
    url: https://github.com/OpenRA/OpenRA/releases

desktop:
  Desktop Entry:
    Type: Application
    Version: 1.0
    Name: OpenRA - Dune 2000
    GenericName: Real Time Strategy Game
    GenericName[de]: Echtzeit-Strategiespiel
    Comment: Reimagining of early Westwood Games
    Icon: openra-d2k
    Exec: openra-d2k %U
    Terminal: false
    Categories: Game
    MimeType: x-scheme-handler/openra-d2k-release-20190314
    StartupWMClass: openra-d2k-release-20190314
  AppImageHub:
    X-AppImage-UpdateInformation: zsync|https://master.openra.net/appimagecheck?mod=d2k&channel=release
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0
---
