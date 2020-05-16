---
layout: app

permalink: /BioTracker/
description: Tracking application

icons:
  - BioTracker/icons/800x800/BT3-big.png

screenshots:
  - BioTracker/screenshot.png

authors:
  - name: BioroboticsLab
    url: https://github.com/BioroboticsLab

links:
  - type: GitHub
    url: BioroboticsLab/biotracker_core
  - type: Download
    url: https://github.com/BioroboticsLab/biotracker_core/releases

desktop:
  Desktop Entry:
    Type: Application
    Name: BioTracker
    Exec: BioTracker
    Icon: BT3-big
    Comment: Tracking application
    Terminal: true
    Categories: Science
  AppImageHub:
    X-AppImage-UpdateInformation: zsync|https://git.imp.fu-berlin.de/bioroboticslab/biotracker/biotracker/-/jobs/artifacts/master/raw/BioTracker-x86_64.AppImage.zsync?job=package
      ubuntu-18.04
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
