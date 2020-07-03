---
layout: app

permalink: /SmuView/
description: Power supplies, electronic loads, multimeters and more.
license: GPL-3.0+

icons:
  - SmuView/icons/scalable/smuview.svg
screenshots:
- https://sigrok.org/wimg/3/32/Sv_with_load.png

authors:
  - name: knarfS
    url: https://github.com/knarfS

links:
  - type: GitHub
    url: knarfS/smuview
  - type: Download
    url: https://github.com/knarfS/smuview/releases

desktop:
  Desktop Entry:
    Name: SmuView
    GenericName: A sigrok GUI for power supplies, loads and measurement devices
    Categories: Development
    Comment: SmuView is a Qt based source measure unit GUI for sigrok.
    Exec: smuview
    Icon: smuview
    Type: Application
    X-AppImage-Version: 0.0.3
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

appdata:
  Type: desktop-application
  ID: org.sigrok.SmuView.desktop
  Name:
    C: SmuView
  Summary:
    C: Power supplies, electronic loads, multimeters and more.
  Description:
    C: >-
      <p>SmuView is a Qt based source measure unit GUI for sigrok.</p>
  
      <p>Features:</p>
  
      <ul>
        <li>Remote control devices</li>
        <li>Data acquisition</li>
        <li>Multiple devices at the same time</li>
        <li>Math channels</li>
        <li>Data export as CSV</li>
      </ul>
  ProjectLicense: GPL-3.0+
  Url:
    homepage: http://sigrok.org/wiki/SmuView
    bugtracker: https://github.com/knarfS/smuview/issues
    faq: http://sigrok.org/wiki/FAQ
  Launchable:
    desktop-id:
    - org.sigrok.SmuView.desktop
  Provides:
    binaries:
    - smuview
  Screenshots:
  - default: true
    thumbnails: []
    source-image:
      url: https://sigrok.org/wimg/3/32/Sv_with_load.png
      lang: C
---
