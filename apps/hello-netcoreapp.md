---
layout: app

permalink: /hello-netcoreapp/
description: Print Hello World
license: GPL

icons:
  - hello-netcoreapp/icons/scalable/hello-netcoreapp.svg

authors:
  - name: philippgille
    url: https://github.com/philippgille

links:
  - type: GitHub
    url: philippgille/hello-netcoreapp
  - type: Download
    url: https://github.com/philippgille/hello-netcoreapp/releases

desktop:
  Desktop Entry:
    Type: Application
    Name: hello-netcoreapp
    Comment: Self-contained .NET Core console application that prints Hello World
    Icon: hello-netcoreapp
    Exec: hello-netcoreapp
    Path: "~"
    Terminal: true
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

appdata:
  Type: console-application
  ID: com.philippgille.hello-netcoreapp
  Name:
    C: hello-netcoreapp
  Summary:
    C: Print Hello World
  Description:
    C: >-
      <p>hello-netcoreapp is a basic .NET Core console application that prints &quot;Hello World!&quot;. Its source code repository
      contains additional scripts and files for building the app and creating release artifacts for a framework-dependent deployment
      (FDD), self-contained deployment (SCD), Docker image, Chocolatey package and AppImage. So the purpose of this app is not
      the app itself, but to showcase how to build the aforementioned release artifacts.</p>
  DeveloperName:
    C: Philipp Gille
  ProjectLicense: GPL
  Categories:
  - Development
  Url:
    homepage: https://github.com/philippgille/hello-netcoreapp
  Provides:
    binaries:
    - hello-netcoreapp
  Releases:
  - version: 0.1.0
---
