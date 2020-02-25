---
layout: app

permalink: /qavrdude/
description: Graphical interface to the Avrdude programmer

icons:
  - qavrdude/icons/scalable/qavrdude.svg

screenshots:
  - qavrdude/screenshot.png

authors:
  - name: probonopd
    url: https://github.com/probonopd

links:
  - type: GitHub
    url: probonopd/avrdude-qt-gui
  - type: Download
    url: https://github.com/probonopd/avrdude-qt-gui/releases

desktop:
  Desktop Entry:
    Name: qavrdude
    Comment: Graphical interface to the Avrdude programmer
    Exec: qavrdude
    Icon: qavrdude
    Type: Application
    Categories: Development
    X-AppImage-Version: 2e689f3
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|probonopd|avrdude-qt-gui|continuous|qavrdude*-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
