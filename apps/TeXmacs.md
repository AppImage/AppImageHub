---
layout: app

permalink: /TeXmacs/
description: scientific word processor
license: GPL-3.0

icons:
  - TeXmacs/icons/scalable/TeXmacs.svg
screenshots:
- http://www.texmacs.org/tmweb/images/tmwin1079a.png

authors:
  - name: slowphil
    url: https://build.opensuse.org/user/show/slowphil

links:
  - type: Download
    url: https://download.opensuse.org/repositories/home:/slowphil:/texmacs-devel/AppImage/texmacs-latest-x86_64.AppImage.mirrorlist

desktop:
  Desktop Entry:
    Name: GNU TeXmacs
    Comment: A structured wysiwyg scientific text editor
    BinaryPattern: texmacs
    Protocols: 
    MimeType: text/x-texmacs
    Exec: texmacs %f
    Icon: TeXmacs
    TerminalOptions: 
    Path: 
    Type: Application
    Terminal: 0
    MapNotify: false
    Categories: Education
  AppImageHub:
    X-AppImage-UpdateInformation: zsync|https://download.opensuse.org/repositories/home:/slowphil:/texmacs-devel/AppImage/texmacs-latest-x86_64.AppImage.zsync
    X-AppImage-Signature: 'Signature made Wed 31 Jul 2019 09:12:20 AM UTC using RSA
      key ID C5B8CA84 Can''t check signature: No public key'
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

appdata:
  Type: desktop-application
  ID: texmacs
  Name:
    C: TeXmacs
  Summary:
    C: scientific word processor
  Description:
    C: >-
      <p>GNU TeXmacs is a scientific word processor of the GNU project with WYSIWYW (what you see is what you want) user interface
      and top-quality typesetting algorithms. It was inspired by TeX and GNU Emacs, though it shares no code with those programs.</p>
  ProjectLicense: GPL-3.0
  Url:
    homepage: http://www.texmacs.org/tmweb/home/welcome.en.html
  Launchable:
    desktop-id:
    - texmacs.desktop
  Screenshots:
  - default: true
    thumbnails: []
    source-image:
      url: http://www.texmacs.org/tmweb/images/tmwin1079a.png
      lang: C
---
