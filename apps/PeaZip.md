---
layout: app

permalink: /PeaZip/
description: Free Zip / Unzip software and Rar file extractor
license: MIT

icons:
  - PeaZip/icons/256x256/peazip.png

screenshots:
  - PeaZip/screenshot.png

authors:
  - name: ferion11
    url: https://github.com/ferion11

links:
  - type: GitHub
    url: ferion11/PeaZip_Appimage
  - type: Download
    url: https://github.com/ferion11/PeaZip_Appimage/releases

desktop:
  Desktop Entry:
    Version: 1.0
    Encoding: UTF-8
    Name: PeaZip
    MimeType: application/x-gzip
    GenericName: Archiving Tool
    Comment: Free Zip / Unzip software and Rar file extractor
    Exec: AppRun
    Icon: peazip
    Type: Application
    Terminal: false
    X-KDE-HasTempFileOption: true
    Categories: GTK
    Name[en_US]: PeaZip
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|ferion11|$P_NAME_Appimage|continuous|$P_NAME-v${P_VERSION}-*arch*.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT
---
