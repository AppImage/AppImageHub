---
layout: app

permalink: /ScanTailor/
description: An interactive post-processing tool for scanned pages.
license: GPL-3.0-or-later

icons:
  - ScanTailor/icons/scalable/scantailor.svg

authors:
  - name: probonopd
    url: https://github.com/probonopd

links:
  - type: GitHub
    url: probonopd/scantailor
  - type: Download
    url: https://github.com/probonopd/scantailor/releases

desktop:
  Desktop Entry:
    Name: ScanTailor
    Exec: scantailor
    GenericName: Scan processing software
    GenericName[ru]: Постобработка отсканированных страниц
    Comment: Interactive post-processing tool for scanned pages
    Comment[af]: Interaktiewe post-verwerkings hulpmiddel vir geskandeerde bladsye
    Comment[sq]: Mjet interaktiv pas përpunimi për faqet e skanuara
    Comment[ast]: Ferramienta interactiva de postprocesamientu pa páxines escaneaes
    Comment[bn]: স্ক্যানকৃত পৃষ্ঠার জন্য মিথস্ক্রিয় পোস্ট-প্রসেসিং টুল
    Comment[bs]: Interaktivni alat za naknadnu obradu optički skeniranih stranica
    Comment[pt_BR]: Ferramenta interativa de pós processamento para páginas digitalizadas
    Comment[bg]: Инструмент за интерактивна пост обработка на сканирани страници
    Comment[ca]: Eina interactiva de postprocessament de pàgines escanejades
    Comment[ca@valencia]: Eina interactiva de postprocessament de pàgines escanejades
    Comment[zh_HK]: 掃描紙張的互動式後製工具
    Comment[zh_TW]: 掃描紙張的互動式後製工具
    Comment[zh_CN]: 用于扫描页面的交互式后期处理工具
    Comment[crh]: Taranmış sayfalar için etkileşimli son işlem aracı
    Comment[cs]: Interaktivní nástroj pro zpracování naskenovaných stránek
    Comment[et]: Skaneeritud lehekülgede interaktiivne järeltöötlus vahend
    Comment[da]: Interaktivt efterbehandlingsværktøj til skannede sider
    Comment[nl]: Interactief, post-processing hulpmiddel voor gescande pagina"s
    Comment[fi]: Interaktiivinen jälkikäsittelytyökalu skannatuille sivuille
    Comment[fr]: Interactive outil de post-traitement pour des pages numérisées
    Comment[gl]: Ferramenta interactiva de postprocesamento de imaxes dixitalizadas
    Comment[el]: Διαδραστικό εργαλείο post-processing για σελίδες που έχουν σαρωθεί
    Comment[de]: Interaktives Nachbearbeitungswerkzeug für gescannte Seiten
    Comment[hu]: Beolvasott képek interaktív utófeldolgozása
    Comment[ja]: スキャンされたページを対話式に後処理するツール
    Comment[it]: Strumento interattivo per il post processamento di pagine acquisite
      con lo scanner
    Comment[ky]: Сканерленген баракчаларды кайра иштетүү үчүн интерактивдүү шайман
    Comment[ms]: Alat post-pemprosesan berinteraktif untuk halaman terimbas
    Comment[nb]: Interaktivt verktøy for etterbehandling av skannede sider
    Comment[oc]: Aisina interactiva de tractament de document aprèp numerizacion
    Comment[pl]: Program do obróbki i przetwarzana zeskanowanych dokumentów tekstowych
    Comment[pt]: Ferramenta de pós-processamento interactivo de páginas scaneadas
    Comment[ro]: Utilitar interactiv pentru post-procesare pagini scanate
    Comment[ru]: Интерактивный инструмент постобработки для отсканированных страниц
    Comment[sl]: Vzajemno orodje za poopravilo optično prebranih strani
    Comment[es]: Herramienta interactiva de postprocesamiento para páginas escaneadas
    Comment[sv]: Interaktivt vektyg för efterbearbetning av inlästa sidor
    Comment[vi]: Công cụ tương tác xử lý trước các trang được quét
    Comment[uk]: Інтерактивний інструмент пост-обробки відсканованих сторінок
    Comment[tr]: Taranmış sayfalar için etkileşimli son işlem aracı
    Type: Application
    Icon: scantailor
    Terminal: false
    MimeType: application/x-scantailor
    Categories: Graphics
    X-AppImage-Version: f01f936
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|probonopd|scantailor|continuous|ScanTailor*-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: NOASSERTION

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
