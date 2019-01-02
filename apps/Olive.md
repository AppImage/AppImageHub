---
layout: app

permalink: /Olive/
description: Non-linear video editor
license: GPLv3

icons:
  - Olive/icons/128x128/org.olivevideoeditor.Olive.png
screenshots:
- http://images.libregraphicsworld.org/video/2018/12/introducing-olive/olive-alpha-main-window.jpg

authors:
  - name: olive-editor
    url: https://github.com/olive-editor

links:
  - type: GitHub
    url: olive-editor/olive
  - type: Download
    url: https://github.com/olive-editor/olive/releases

desktop:
  Desktop Entry:
    Name: Olive
    Comment: Professional open-source non-linear video editor
    Exec: olive-editor
    Icon: org.olivevideoeditor.Olive
    Terminal: false
    Type: Application
    Categories: AudioVideo
    MimeType: application/vnd.olive-project
    StartupNotify: true
    X-AppImage-Version: .inf
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|olive-editor|olive|continuous|Olive*-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

appdata:
  Type: desktop-application
  ID: org.olivevideoeditor.Olive
  Name:
    C: Olive
  Summary:
    ru: Нелинейный видеоредактор
    C: Non-linear video editor
    es: Editor de video no lineal
    pt_BR: Editor de vídeo não-linear
  Description:
    C: >-
      <p>Olive — свободный нелинейный видеоредактор, задуманный как полноценная замена закрытым коммерческим продуктам.</p>
  DeveloperName:
    C: Olive Team
  ProjectLicense: GPLv3
  Url:
    homepage: https://www.olivevideoeditor.org
    help: https://github.com/olive-editor/olive/issues
    donation: https://www.patreon.com/olivevideoeditor
  Screenshots:
  - default: true
    thumbnails: []
    source-image:
      url: http://images.libregraphicsworld.org/video/2018/12/introducing-olive/olive-alpha-main-window.jpg
      lang: C
  Releases:
  - version: '20181223'
    unix-timestamp: 1545523200
  - version: '20181130'
    unix-timestamp: 1543536000
  ContentRating:
    oars-1.1: {}
---
