---
layout: app

permalink: /FreeCAD/
description: An open source parametric 3D CAD modeler
license: LGPL-2.1

icons:
  - FreeCAD/icons/64x64/freecad_conda.png
screenshots:
- https://www.freecadweb.org/wiki/images/2/2d/FreeCAD011.png

authors:
  - name: FreeCAD
    url: https://github.com/FreeCAD

links:
  - type: GitHub
    url: FreeCAD/FreeCAD
  - type: Download
    url: https://github.com/FreeCAD/FreeCAD/releases

desktop:
  Desktop Entry:
    Version: 1.0
    Name: FreeCAD Conda
    Exec: AppRun
    Icon: freecad_conda
    Type: Application
    Categories: Engineering
    Comment: Feature based Parametric Modeler
    Terminal: false
    StartupNotify: true
    NoDisplay: false
    MimeType: application/x-extension-fcstd
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|FreeCAD|FreeCAD|latest|FreeCAD*glibc2.12-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

appdata:
  Type: desktop-application
  ID: org.freecadweb.FreeCAD
  Name:
    C: FreeCAD
  Summary:
    C: An open source parametric 3D CAD modeler
  Description:
    C: >-
      <p>FreeCAD is a parametric 3D modeler. Parametric modeling
            allows you to easily modify your design by going back into
            your model history and changing its parameters. FreeCAD is
            open source (LGPL license) and completely modular, allowing
            for very advanced extension and customization.</p>
      <p>FreeCAD is multiplatfom, and reads and writes many open
            file formats such as STEP, IGES, STL and others.</p>
  DeveloperName:
    C: The FreeCAD Team
  ProjectLicense: LGPL-2.1
  Url:
    homepage: https://www.freecadweb.org
    bugtracker: https://www.freecadweb.org/tracker
    help: https://forum.freecadweb.org
    donation: https://www.freecadweb.org/wiki/Donate
  Screenshots:
  - default: true
    thumbnails: []
    source-image:
      url: https://www.freecadweb.org/wiki/images/2/2d/FreeCAD011.png
      lang: C
  Releases:
  - version: 0.18.13500
    unix-timestamp: 1562889600
  ContentRating:
    oars-1.1: {}
---
