---
layout: app

permalink: /Tectonic/
description: Tectonic is a modernized, complete, self-contained TeX/LaTeX engine, powered by XeTeX and TeXLive.
license: NOASSERTION

icons:
  - Tectonic/icons/scalable/tectonic.svg

screenshots:
  - Tectonic/screenshot.png

authors:
  - name: tectonic-typesetting
    url: https://github.com/tectonic-typesetting

links:
  - type: GitHub
    url: tectonic-typesetting/tectonic
  - type: Download
    url: https://github.com/tectonic-typesetting/tectonic/releases

desktop:
  Desktop Entry:
    Version: 1.0
    Type: Application
    Name: Tectonic
    Comment: Tectonic is a modernized, complete, self-contained TeX/LaTeX engine, powered
      by XeTeX and TeXLive.
    Categories: ConsoleOnly
    TryExec: tectonic
    Exec: tectonic %F
    Icon: tectonic
    Terminal: true
    MimeType: image/svg+xml
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|tectonic-typesetting|tectonic|continuous|tectonic-*.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: NOASSERTION
---
