---
layout: app

permalink: /Nephtys_Client/
description: OpenSource MMORPG client
license: MIT

icons:
  - Nephtys_Client/icons/128x128/nephtys_icon.png
screenshots:
- https://www.freedesktop.org/software/appstream/docs/images/scr-examples/geany-good.png

authors:

links:

desktop:
  Desktop Entry:
    Type: Application
    Name: nephtys_client
    Exec: nephtys_client
    Icon: nephtys_icon
    Categories: Development
    X-AppImage-Version: 0.0.1
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

appdata:
  Type: desktop-application
  ID: org.nephtys.client.desktop
  Name:
    C: nephtys_client
  Summary:
    C: OpenSource MMORPG client
  Description:
    C: >-
      <p>Written in c++17</p>
  ProjectLicense: MIT
  Url:
    homepage: https://github.com/Milerius/nephtys
  Launchable:
    desktop-id:
    - org.nephtys.client.desktop
  Screenshots:
  - default: true
    thumbnails: []
    source-image:
      url: https://www.freedesktop.org/software/appstream/docs/images/scr-examples/geany-good.png
      lang: C
---
