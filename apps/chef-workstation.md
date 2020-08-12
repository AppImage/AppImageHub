---
layout: app

permalink: /chef-workstation/
description: Tray application for Chef Workstation.
license: Apache-2.0

icons:
  - chef-workstation/icons/128x128/chef-workstation.png

screenshots:
  - chef-workstation/screenshot.png

authors:
  - name: chef
    url: https://github.com/chef

links:
  - type: GitHub
    url: chef/chef-workstation-tray
  - type: Download
    url: https://github.com/chef/chef-workstation-tray/releases

desktop:
  Desktop Entry:
    Name: Chef Workstation
    Comment: Tray application for Chef Workstation.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: chef-workstation
    StartupWMClass: Chef Workstation
    X-AppImage-Version: 0.0.12
    Categories: Development
    X-AppImage-BuildId: 19GDqgIf4yX0oLvJg2QdwSUI3Xt
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: Apache-2.0

electron:
  description: Tray application for Chef Workstation.
  repository: https://github.com/chef/chef-workstation-tray
  author:
    name: Chef Software, Inc.
    email: beta@chef.io
    url: https://chef.sh
  main: main.js
  dependencies:
    electron-is: "^3.0.0"
    electron-osx-appearance: "^0.1.1"
    electron-updater: 3.1.1
---
