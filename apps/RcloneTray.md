---
layout: app

permalink: /RcloneTray/
description: Simple Rclone bookmark manager GUI.
license: MIT

icons:
  - RcloneTray/icons/128x128/rclonetray.png

screenshots:
  - RcloneTray/screenshot.png

authors:
  - name: dimitrov-adrian
    url: https://github.com/dimitrov-adrian

links:
  - type: GitHub
    url: dimitrov-adrian/RcloneTray
  - type: Download
    url: https://github.com/dimitrov-adrian/RcloneTray/releases

desktop:
  Desktop Entry:
    Name: RcloneTray
    Comment: Simple Rclone bookmark manager GUI.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: rclonetray
    StartupWMClass: RcloneTray
    X-AppImage-Version: 0.0.0
    Categories: Utility
    X-AppImage-BuildId: 1CtypEXgFSUHiM5hr75DwOmIp6h
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  version: 0.0.0
  description: Simple Rclone bookmark manager GUI.
  repository:
    type: git
    url: https://github.com/dimitrov-adrian/RcloneTray
  author: Adrian Dimitrov <dimitrov.adrian@gmail.com>
  bugs:
    url: https://github.com/dimitrov-adrian/RcloneTray/issues
  license: MIT
  main: src/main.js
  dependencies:
    adm-zip: "^0.4.11"
    chokidar: "^2.0.4"
    electron-context-menu: "^0.10.1"
    electron-updater: "^3.2.2"
    electron-is-dev: "^1.0.1"
    form-serialize: "^0.7.2"
    ini: "^1.3.5"
---