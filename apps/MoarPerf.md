---
layout: app

permalink: /MoarPerf/
description: Front-end for MoarVM's / Rakudo's profilers

icons:
  - MoarPerf/icons/256x256/moarperf_stolen_icon.png

authors:
  - name: timo
    url: https://github.com/timo

links:
  - type: GitHub
    url: timo/moarperf
  - type: Download
    url: https://github.com/timo/moarperf/releases

desktop:
  Desktop Entry:
    Name: MoarPerf
    Comment: Front-end for MoarVM's / Rakudo's profilers
    Exec: moarperf-appimage-launcher
    Icon: moarperf_stolen_icon
    Terminal: false
    Type: Application
    StartupNotify: false
    Categories: Development
    X-AppImage-Version: ".glibc2.14"
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|timo|moarperf|continuous|MoarPerf*-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---