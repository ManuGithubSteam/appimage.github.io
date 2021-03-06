---
layout: app

permalink: /tweet-tray/
description: Tweet quickly from the desktop without any more distractions.
license: MIT

screenshots:
  - tweet-tray/screenshot.png

authors:
  - name: jonathontoon
    url: https://github.com/jonathontoon

links:
  - type: GitHub
    url: jonathontoon/tweet-tray
  - type: Download
    url: https://github.com/jonathontoon/tweet-tray/releases

desktop:
  Desktop Entry:
    Name: Tweet Tray
    Comment: Tweet quickly from the desktop without any more distractions.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: tweet-tray
    X-AppImage-Version: 1.1.0
    X-AppImage-BuildId: 9e514130-2e40-11a8-3c18-cd69d2b01007
    Categories: Development
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
  description: Tweet quickly from the desktop without any more distractions.
  main: "./main.prod.js"
  author:
    name: Jonathon Toon
    email: jonathontoon@gmail.com
    url: https://github.com/jonathontoon
  license: MIT
  dependencies: {}
---
