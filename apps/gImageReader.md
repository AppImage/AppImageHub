---
layout: app

permalink: /gImageReader/
description: A graphical (qt5) frontend to tesseract-ocr
license: GPL-3.0+

icons:
  - gImageReader/icons/128x128/gimagereader.png
screenshots:
- https://raw.githubusercontent.com/manisandro/gImageReader/gh-pages/gimagereader-qt5.jpg

authors:
  - name: probonopd
    url: https://github.com/probonopd

links:
  - type: GitHub
    url: probonopd/gImageReader
  - type: Download
    url: https://github.com/probonopd/gImageReader/releases

desktop:
  Desktop Entry:
    Name: gImageReader
    GenericName: OCR application
    GenericName[ar_SA]: برنامج التعرف الضوئي للمستندات المصورة
    GenericName[cs]: optické rozpoznávání znaků (OCR)
    GenericName[de]: Texterkennung
    GenericName[es_ES]: Aplicación para OCR
    GenericName[eu]: OCR aplikazioa
    GenericName[fr]: Application OCR
    GenericName[ie]: Application OCR
    GenericName[it]: Applicazione OCR
    GenericName[ko]: OCR 응용 프로그램
    GenericName[nb_NO]: Tekstgjenkjenningsprogram
    GenericName[nl]: OCR-applicatie
    GenericName[pt]: Aplicativo de OCR
    GenericName[pt_BR]: Aplicativo de OCR
    GenericName[ru]: Приложение OCR
    GenericName[uk]: OCR-додаток
    GenericName[zh_CN]: OCR 应用程序
    GenericName[zh_HK]: OCR 應用程式
    GenericName[zh_TW]: OCR 應用程式
    Exec: gimagereader-qt5 %U
    Icon: gimagereader
    Terminal: false
    Type: Application
    StartupNotify: true
    StartupWMClass: gimagereader-qt5
    Categories: Graphics
    MimeType: image/bmp
    Keywords: OCR
    X-AppImage-Version: f01faae
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|probonopd|gImageReader|continuous|gImageReader*-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-3.0

appdata:
  Type: desktop-application
  ID: gimagereader-qt5.desktop
  Name:
    cs_CZ: gImageReader
    C: gImageReader
  Summary:
    cs_CZ: Grafická (qt5) nadstavba pro engine tesseract-ocr
    C: A graphical (qt5) frontend to tesseract-ocr
  Description:
    cs_CZ: >-
      <p>gImageReader je jednoduše použitelná aplikace pro rozpoznávání textu z obrázků, využívající OCR engine tesseract. Mezi
      funkce patří:</p>
  
      <ul>
        <li>Import PDF dokumentů a obrázků z počítače, skenovacích zařízení, schránky a snímků obrazovky</li>
        <li>Zpracování vícero obrázků a dokumentů naráz</li>
        <li>Ruční nebo automatická definice oblasti k rozpoznávání</li>
        <li>Rozpoznání do holého textu nebo hOCR dokumentů</li>
        <li>Rozpoznaný text je zobrazen hned vedle zdrojového obrázku</li>
        <li>Následné zpracování rozpoznaného textu včetně kontroly překlepů</li>
        <li>Vytváření PDF/ODT dokumentů z hOCR dokumentů</li>
      </ul>
    C: >-
      <p>gImageReader is a simple optical character recognition (OCR) application which acts as a frontend to the tesseract
      OCR engine. Features include:</p>
  
      <ul>
        <li>Import PDF documents and images from disk, scanning devices, clipboard and screenshots</li>
        <li>Process multiple images and documents in one go</li>
        <li>Manual or automatic recognition area definition</li>
        <li>Recognize to plain text or to hOCR documents</li>
        <li>Recognized text displayed directly next to the image</li>
        <li>Post-process the recognized text, including spellchecking</li>
        <li>Generate PDF/ODT documents from hOCR documents</li>
      </ul>
  ProjectLicense: GPL-3.0+
  Keywords:
    cs_CZ:
    - ocr
    - optické
    - rozpoznávání
    - tesseract
    - pdf
    C:
    - ocr
    - optical
    - recognition
    - tesseract
    - pdf
    - qt5
  Url:
    bugtracker: https://github.com/manisandro/gImageReader/issues
    faq: https://github.com/manisandro/gImageReader/wiki/FAQ
    homepage: https://github.com/manisandro/gImageReader
    translate: https://github.com/manisandro/gImageReader/blob/master/README.md
  Launchable:
    desktop-id:
    - gimagereader-qt5.desktop
  Provides:
    binaries:
    - gimagereader-qt5
  Screenshots:
  - default: true
    caption:
      C: gImageReader-qt5
    thumbnails: []
    source-image:
      url: https://raw.githubusercontent.com/manisandro/gImageReader/gh-pages/gimagereader-qt5.jpg
      lang: C
  Releases:
  - version: 3.3.0
    unix-timestamp: 1537920000
  ContentRating:
    oars-1.0:
      social-info: mild
---
