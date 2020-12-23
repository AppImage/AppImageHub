---
layout: app

permalink: /MusE/
description: Digital Audio Workstation
license: GPL-2.0+

icons:
  - MusE/icons/150x150/muse.png
screenshots:
- https://muse-sequencer.github.io/img/arranger_new.png

authors:
  - name: muse-sequencer
    url: https://github.com/muse-sequencer

links:
  - type: GitHub
    url: muse-sequencer/muse
  - type: Download
    url: https://github.com/muse-sequencer/muse/releases

desktop:
  Desktop Entry:
    Name: MusE
    GenericName: Digital Audio Workstation
    GenericName[fr]: Séquenceur audio/MIDI
    Comment: A music editor for Linux
    Comment[fr]: Éditeur MIDI de musique
    Icon: muse
    Type: Application
    Exec: muse4
    Terminal: false
    Categories: Sequencer
    MimeType: audio/midi
    X-AppImage-Version: master
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

appdata:
  Type: desktop-application
  ID: org.musesequencer.Muse4
  Name:
    C: MusE
  Summary:
    C: Digital Audio Workstation
  Description:
    C: >-
      <p>MusE is a MIDI/Audio sequencer with recording and editing capabilities. It can
            perform audio effects like chorus/flanger in real-time via LASH and it supports
            Jack and ALSA interfaces. MusE aims to be a complete multitrack virtual studio
            for Linux.</p>
  ProjectLicense: GPL-2.0+
  Url:
    homepage: https://muse-sequencer.github.io/
  Launchable:
    desktop-id:
    - org.musesequencer.muse4.desktop
  Provides:
    binaries:
    - muse4
  Screenshots:
  - default: true
    thumbnails: []
    source-image:
      url: https://muse-sequencer.github.io/img/arranger_new.png
      lang: C
  - thumbnails: []
    source-image:
      url: https://muse-sequencer.github.io/img/midi.png
      lang: C
  - thumbnails: []
    source-image:
      url: https://muse-sequencer.github.io/img/drum.png
      lang: C
  - thumbnails: []
    source-image:
      url: https://muse-sequencer.github.io/img/wave.png
      lang: C
  - thumbnails: []
    source-image:
      url: https://muse-sequencer.github.io/img/mixer.png
      lang: C
  Releases:
  - version: 4.0.0-pre1
    unix-timestamp: 1605398400
    description:
      C: "<p>Apart from the usual bunch of bug fixes and improvements \n        the most prominent new feature is the new tabbed
        UI with docks! \n        By default now with a dark theme.</p>"
  ContentRating:
    oars-1.0:
      language-humor: none
---
