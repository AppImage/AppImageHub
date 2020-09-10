---
layout: app

permalink: /DivvyDroid/
description: Application to screencast and remote control Android devices
license: GPL-3.0+

icons:
  - DivvyDroid/icons/scalable/divvydroid.svg
screenshots:
- https://raw.githubusercontent.com/maxrd2/DivvyDroid/master/pkg/screenshot.png

authors:
  - name: maxrd2
    url: https://github.com/maxrd2

links:
  - type: GitHub
    url: maxrd2/DivvyDroid
  - type: Download
    url: https://github.com/maxrd2/DivvyDroid/releases

desktop:
  Desktop Entry:
    Type: Application
    Name: DivvyDroid
    GenericName: Android Remote Control
    Comment: Application to screencast and remote control Android devices
    Icon: divvydroid
    Exec: divvydroid
    Terminal: false
    Categories: Qt
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|maxrd2|DivvyDroid|latest|DivvyDroid*-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

appdata:
  Type: desktop-application
  ID: net.smoothware.divvydroid
  Name:
    C: DivvyDroid
  Summary:
    C: Application to screencast and remote control Android devices
  Description:
    C: >-
      <p>DivvyDroid is an Qt/C++ application for remote controlling you Android device. It implements ADB TCP client.</p>
  
      <ul>
        <li>Requires ADB to be installed and in PATH, root will help on some devices</li>
        <li>Direct device communication over internal ADB client and TCP</li>
        <li>Fast android device display streaming using screenrecord (H.264)</li>
        <li>Fast and accurate keyboard and touch handling using android monkey and by direct writes to device&apos;s /dev/input</li>
        <li>Fallback to display streaming using screencap (JPEG, PNG, RAW)</li>
        <li>Fallback to slow adb shell input command, when monkey is unavailable or without permissions to write to /dev/input</li>
      </ul>
  ProjectLicense: GPL-3.0+
  Url:
    homepage: https://github.com/maxrd2/divvydroid
  Launchable:
    desktop-id:
    - divvydroid.desktop
  Provides:
    binaries:
    - divvydroid
  Screenshots:
  - default: true
    caption:
      C: Main application window
    thumbnails: []
    source-image:
      url: https://raw.githubusercontent.com/maxrd2/DivvyDroid/master/pkg/screenshot.png
      lang: C
  Releases:
  - version: 1.0.0
    unix-timestamp: 1558137600
---
