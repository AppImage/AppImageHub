---
layout: app

permalink: /ScanTailor_Advanced/
description: An interactive post-processing tool for scanned pages.
license: GPL-3.0-or-later

icons:
  - ScanTailor_Advanced/icons/scalable/ScanTailor.svg

authors:
  - name: probonopd
    url: https://github.com/probonopd

links:
  - type: GitHub
    url: probonopd/scantailor-advanced
  - type: Download
    url: https://github.com/probonopd/scantailor-advanced/releases

desktop:
  Desktop Entry:
    Version: 1.0
    Name: ScanTailor Advanced
    Comment: Interactive post-processing tool for scanned pages
    Exec: scantailor %f
    Icon: ScanTailor
    Terminal: false
    X-MultipleArgs: false
    Type: Application
    Categories: Graphics
    MimeType: application/x-scantailor-project
    X-AppImage-Version: 7585828
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|probonopd|scantailor-advanced|continuous|ScanTailor_Advanced*-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

appdata:
  Type: desktop-application
  ID: org.scantailor.ScanTailor
  Name:
    C: ScanTailor
  Summary:
    C: An interactive post-processing tool for scanned pages.
  Description:
    C: >-
      <p>Scan Tailor is an interactive post-processing tool for scanned pages.
            It performs operations such as page splitting, deskewing, adding/removing borders, and others.
            You give it raw scans, and you get pages ready to be printed or assembled into a PDF or DJVU file.
            Scanning, optical character recognition, and assembling multi-page documents are out of scope of this project.</p>
      <p>Scan Tailor is Free Software (which is more than just freeware).
            It’s written in C++ with Qt and released under the General Public License version 3.
            We develop both Windows and GNU/Linux versions.</p>
      <p>This project started in late 2007 and by mid 2010 it reached production quality. In 2014,
            the original developer Joseph Artsimovich stepped aside, and Nate Craun took over as the new maintainer.</p>
      <p>Scan Tailor is being used not just by enthusiasts, but also by libraries and other institutions.
            A few books processed by Scan Tailor even ended up on Google Books.</p>
  ProjectLicense: GPL-3.0-or-later
  Url:
    bugtracker: https://github.com/scantailor/scantailor/issues
    homepage: http://scantailor.org/
  Launchable:
    desktop-id:
    - scantailor.desktop
  Releases:
  - version: 0.9.12.1
    unix-timestamp: 1462147200
  ContentRating:
    oars-1.1: {}
---
