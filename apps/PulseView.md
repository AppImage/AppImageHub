---
layout: app

permalink: /PulseView/
description: Logic analyzer, oscilloscope and MSO GUI
license: GPL-3.0+

icons:
  - PulseView/icons/scalable/pulseview.svg
screenshots:
- http://sigrok.org/wimg/e/ee/PulseView_I2C_DS1307_Decode.png

authors:

links:

desktop:
  Desktop Entry:
    Name: PulseView
    GenericName: Logic analyzer, oscilloscope and MSO GUI
    Categories: Development
    Comment: Control your logic analyzer, oscilloscope, or MSO
    Exec: pulseview
    Icon: pulseview
    Type: Application
    MimeType: application/vnd.sigrok.session
    X-AppImage-Version: NIGHTLY
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

appdata:
  Type: desktop-application
  ID: org.sigrok.PulseView.desktop
  Name:
    C: PulseView
  Summary:
    C: Logic analyzer, oscilloscope and MSO GUI
  Description:
    C: >-
      <p>PulseView is a Qt based logic analyzer, oscilloscope and MSO GUI for sigrok.</p>
  
      <p>Features:</p>
  
      <ul>
        <li>Fast O(log N) signal rendering at all zoom levels</li>
        <li>Protocol decoder support</li>
        <li>Trace groups support</li>
      </ul>
  ProjectLicense: GPL-3.0+
  Url:
    homepage: http://sigrok.org/wiki/PulseView
    bugtracker: http://sigrok.org/bugzilla/enter_bug.cgi?format=guided&product=PulseView
    faq: http://sigrok.org/wiki/FAQ
  Launchable:
    desktop-id:
    - org.sigrok.PulseView.desktop
  Provides:
    binaries:
    - pulseview
    mimetypes:
    - application/vnd.sigrok.session
  Screenshots:
  - default: true
    thumbnails: []
    source-image:
      url: http://sigrok.org/wimg/e/ee/PulseView_I2C_DS1307_Decode.png
      lang: C
  Suggests:
  - type: upstream
    ids:
    - org.sigrok.sigrok-firmware
    - org.sigrok.sigrok-firmware-fx2lafw
---
