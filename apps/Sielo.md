---
layout: app

permalink: /Sielo/
description: A simple, customizable and fast web browser.

icons:
  - Sielo/icons/256x256/sielo.png

screenshots:
  - Sielo/screenshot.png

authors:
  - name: SieloBrowser
    url: https://github.com/SieloBrowser

links:
  - type: GitHub
    url: SieloBrowser/SieloBrowser
  - type: Download
    url: https://github.com/SieloBrowser/SieloBrowser/releases

desktop:
  Desktop Entry:
    Name: Sielo
    Type: Application
    Icon: sielo
    Categories: Network
    Comment: A simple, customizable and fast web browser.
    Comment[fr]: Un navigateur internet simple, personnalisable et rapide.
    GenericName: Web Browser
    GenericName[fr]: Navigateur Internet
    Exec: sielo-browser
    MimeType: text/html
    Actions: NewTab
  Desktop Action NewTab:
    Name: Open new tab
    Exec: sielo-browser --new-tab
  Desktop Action NewWindow:
    Name: Open new window
    Exec: sielo-browser --new-window
  Desktop Action PrivateBrowsing:
    Name: Start private browsing
    Exec: sielo-browser --private-browsing
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
