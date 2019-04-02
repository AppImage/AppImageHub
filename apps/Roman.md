---
layout: app

permalink: /Roman/
description: A course material builder for online learning systems (tkinter gui)
license: MIT

icons:
  - Roman/icons/1024x1024/roman.png
screenshots:
- https://github.com/apluslms/roman/raw/master/simple_gui/screenshot.png

authors:
  - name: apluslms
    url: https://github.com/apluslms

links:
  - type: GitHub
    url: apluslms/roman
  - type: Download
    url: https://github.com/apluslms/roman/releases

desktop:
  Desktop Entry:
    Version: 1.0
    Type: Application
    Terminal: false
    Exec: "./Roman"
    Icon: roman
    Name: Roman
    Comment: A course material builder for online learning systems (tkinter gui)
    Comment[fi]: Verkkokurssimateriaalin kääntötyökalu (tkinter gui)
    GenericName: Course material builder
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

appdata:
  Type: desktop-application
  ID: io.github.apluslms.Roman.roman_tki
  Name:
    C: Roman
  Summary:
    C: A course material builder for online learning systems (tkinter gui)
  Description:
    C: >-
      <p>Roman is a program used to build course material for online learning systems (LMS).
            Course material is compiled to LMS configrations and presentation files using Docker
            containers. Roman manages this process. In addition, Roman runs validation step to verify
            that the generated configuration is valid and usable by the LMS.</p>
      <p>Roman has been designed specifically to work with A+ online learning system.
            With A+, course material is written in reStructuredText (RST). Material is compiled
            to html and yaml files using Ariel, a tool build on top of Sphinx that contains
            custom extensions for this purpose. Typical course definition includes Ariel as
            a build step.</p>
      <p>Roman requires Docker CE to be installed in your system and you to have access to it.</p>
  DeveloperName:
    C: A+ LMS Team
  ProjectLicense: MIT
  Url:
    homepage: https://github.com/apluslms/roman
  Launchable:
    desktop-id:
    - io.github.apluslms.Roman.roman_tki.desktop
  Screenshots:
  - default: true
    caption:
      C: A successful build
    thumbnails: []
    source-image:
      url: https://github.com/apluslms/roman/raw/master/simple_gui/screenshot.png
      lang: C
---
