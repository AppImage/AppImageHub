---
layout: app

permalink: /VLC/
description: VLC media player, the open-source multimedia player
license: GPL-2.0+

authors:
  - name: darealshinji
    url: https://github.com/darealshinji

links:
  - type: GitHub
    url: darealshinji/vlc-AppImage
  - type: Download
    url: https://github.com/darealshinji/vlc-AppImage/releases

desktop:
  Desktop Entry:
    Version: 1.0
    Name: VLC media player
    GenericName: Media player
    Comment: Read, capture, broadcast your multimedia streams
    Name[bn]: VLC মিডিয়া প্লেয়ার
    Comment[bn]: আপনার মাল্টিমিডিয়া স্ট্রীম পড়ুন, ধরে রাখুন এবং ছড়িয়ে দিন
    Name[br]: VLC lenner mediaoù
    GenericName[br]: Lenner mediaoù
    Comment[br]: Lenn, enrollañ, skignañ ho lanvioù liesvedia
    Name[ca]: Reproductor multimèdia VLC
    GenericName[ca]: Reproductor multimèdia
    Comment[ca]: Reproduïu, captureu i difoneu fluxos multimèdia
    Name[de]: VLC Media Player
    GenericName[de]: Medienwiedergabe
    Comment[de]: Wiedergabe, Aufnahme und Verbreitung Ihrer Multimedia-Streams
    Name[es]: Reproductor multimedia VLC
    GenericName[es]: Reproductor multimedia
    Comment[es]: Lea, capture y emita sus contenidos multimedia
    Name[et]: VLC meediaesitaja
    GenericName[et]: Meediaesitaja
    Comment[et]: Multimeediafailide taasesitamine, lindistamine ja edastamine
    Name[eu]: VLC multimedia irakurgailua
    GenericName[eu]: Multimedia irakurgailua
    Comment[eu]: Irakurri, hartu, igorri zure multimedia jarioak
    Name[fi]: VLC-mediasoitin
    GenericName[fi]: Mediasoitin
    Comment[fi]: Toista, tallenna ja lähetä multimediaa
    Name[fr]: Lecteur multimédia VLC
    GenericName[fr]: Lecteur multimédia
    Comment[fr]: Lire, capturer, diffuser vos flux multimedia
    Name[gl]: Reprodutor multimedia VLC
    GenericName[gl]: Reprodutor multimedia
    Comment[gl]: Lea, capture e emita os seus fluxos multimedia
    Name[he]: נגן המדיה VLC
    GenericName[he]: נגן מדיה
    Comment[he]: קריאה, לכידה ושידור של תזרימי מולטימדיה
    Name[hu]: VLC médialejátszó
    GenericName[hu]: Médialejátszó
    Comment[hu]: Multimédiás adatfolyamok olvasása, mentése, szórása
    Name[is]: VLC margmiðlunarspilarinn
    GenericName[is]: Margmiðlunarspilari
    Comment[is]: Spilar margmiðlunarefni ásamt því að taka upp og útvarpa straumum
    Name[it]: Lettore multimediale VLC
    GenericName[it]: Lettore multimediale
    Comment[it]: Legge, acquisisce e trasmette i tuoi flussi multimediali
    Name[ja]: VLCメディアプレイヤー
    Comment[ja]: マルチメディアストリームの読み込み、キャプチャー、ブロードキャスト
    Name[km]: កម្មវិធី​ចាក់​មេឌៀ VLC
    Comment[km]: អាន ចាប់យក ប្រកាស​ស្ទ្រីម​ពហុមេឌៀ​របស់​អ្នក
    Name[lt]: VLC leistuvė
    GenericName[lt]: Leistuvė
    Comment[lt]: Groti, įrašyti, siųsti įvairialypės terpės kūrinius
    Name[nl]: VLC Media Player
    GenericName[nl]: Mediaspeler
    Comment[nl]: Uw multimediastreams afspelen, opnemen en uitzenden
    Name[nn]: VLC mediespelar
    GenericName[nn]: Mediespelar
    Comment[nn]: Spel av, ta opp og send ut multimedia
    Name[pa]: VLC ਮੀਡਿਆ ਪਲੇਅਰ
    Comment[pa]: ਆਪਣੀ ਮਲਟੀਮੀਡਿਆ ਸਟਰੀਮ ਪੜ੍ਹੋ, ਕੈਪਚਰ ਤੇ ਬਰਾਡਕਾਸਟ ਕਰੋ
    Name[pl]: VLC media player
    GenericName[pl]: Odtwarzacz multimedialny
    Comment[pl]: Odczytywanie, przechwytywanie i nadawanie strumieni multimedialnych
    Name[pt_BR]: Reprodutor de Mídias VLC
    GenericName[pt_BR]: Reprodutor de Mídias
    Comment[pt_BR]: Reproduza, capture e transmita os seus fluxos multimídia
    Name[ru]: Медиаплеер VLC
    GenericName[ru]: Медиаплеер
    Comment[ru]: Универсальный проигрыватель видео и аудио
    Name[sk]: VLC media player
    Comment[sk]: Naèítavajte, zaznamenávajte, vysielajte svoje multimediálne streamy
    Name[sv]: VLC mediaspelare
    GenericName[sv]: Mediaspelare
    Comment[sv]: Spelare för film och musik
    Name[te]: VLC మాధ్యమ ప్రదర్శకం
    GenericName[te]: మాధ్యమ ప్రదర్శకం
    Comment[te]: మీ బహుళమాధ్యమ ప్రవాహాలను చదువు, బంధించు మరియు ప్రసారం చేయి
    Name[wa]: Djouweu d' media VLC
    GenericName[wa]: Djouweu d' media
    Comment[wa]: Lét, egaloye, evoye vos floûs multimedia
    Name[zh_CN]: VLC media player
    GenericName[zh_CN]: 媒体播放器
    Comment[zh_CN]: 为您读取、捕获或发送多媒体流
    Exec: vlc --started-from-file %U
    TryExec: vlc
    Icon: vlc
    Terminal: false
    Type: Application
    Categories: AudioVideo
    MimeType: video/dv
    X-KDE-Protocols: ftp,http,https,mms,rtmp,rtsp,sftp,smb
    Keywords: Player
  AppImageHub:
    X-AppImage-UpdateInformation: false
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

appdata:
  Type: desktop-application
  ID: vlc.desktop
  Name:
    C: VLC
  Summary:
    C: VLC media player, the open-source multimedia player
  Description:
    C: >-
      <p>VLC is a free and open source cross-platform multimedia player and
                  framework that plays most multimedia files as well as DVDs, Audio CDs,
                  VCDs, and various streaming protocols.</p>
  DeveloperName:
    C: VideoLAN et al.
  ProjectGroup: VideoLAN
  ProjectLicense: GPL-2.0+
  Url:
    homepage: https://www.videolan.org/vlc/
    bugtracker: https://trac.videolan.org/vlc/
    donation: https://www.videolan.org/contribute.html
  Screenshots:
  - default: true
    thumbnails: []
  - default: true
    thumbnails: []
  - default: true
    thumbnails: []
  Releases:
  - version: 2.2.6
---
