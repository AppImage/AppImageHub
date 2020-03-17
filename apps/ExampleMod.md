---
layout: app

permalink: /ExampleMod/

icons:
  - ExampleMod/icons/128x128/openra-example.png

screenshots:
  - ExampleMod/screenshot.png

authors:
  - name: OpenRA
    url: https://github.com/OpenRA

links:
  - type: GitHub
    url: OpenRA/OpenRAModSDK
  - type: Download
    url: https://github.com/OpenRA/OpenRAModSDK/releases

desktop:
  Desktop Entry:
    Type: Application
    Version: 1.0
    Name: OpenRA - Example Mod
    GenericName: Real Time Strategy Game
    Icon: openra-example
    Exec: openra-example %u
    Terminal: false
    Categories: Game
    StartupWMClass: openra-example-20180923
    MimeType: x-scheme-handler/openra-example-20180923
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
