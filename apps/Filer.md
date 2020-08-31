---
layout: app

permalink: /Filer/
description: Browse the file system and manage the files
license: GPL-2.0

icons:
  - Filer/icons/256x256/system-file-manager.png

screenshots:
  - Filer/screenshot.png

authors:
  - name: probonopd
    url: https://github.com/probonopd

links:
  - type: GitHub
    url: probonopd/filer
  - type: Download
    url: https://github.com/probonopd/filer/releases

desktop:
  Desktop Entry:
    Type: Application
    Name: Filer File Manager
    GenericName: File Manager
    Comment: Browse the file system and manage the files
    Exec: filer-qt %U
    MimeType: inode/directory
    Icon: system-file-manager
    Categories: FileManager
    StartupNotify: true
    Name[de]: Filer-Qt
    GenericName[de]: Dateimanager
    Comment[de]: Dateimanager der Desktop-Umgebung LXQt
    Name[el]: Διαχειριστής αρχείων Filer
    GenericName[el]: Διαχειριστής αρχείων
    Comment[el]: Περιήγηση του συστήματος αρχείων και διαχείριση των αρχείων
    Name[hu]: Filer-Qt fájlkezelő
    GenericName[hu]: Fájlkezelő
    Comment[hu]: Fájlok böngészése és karbantartása
    Name[it]: Gestore file PCmanFM
    GenericName[it]: Gestore file
    Comment[it]: Esplora e organizza file e cartelle
    Name[pl]: Menedżer plików Filer
    GenericName[pl]: Menedżer plików
    Comment[pl]: Przegląd systemu plików i zarządzanie plikami
    Name[pt]: Gestor de ficheiros Filer
    GenericName[pt]: Gestor de ficheiros
    Comment[pt]: Explorar o sistema de ficheiros e gerir os seus ficheiros e pastas
    X-AppImage-Version: 27
  AppImageHub:
    X-AppImage-UpdateInformation: gh-releases-zsync|probonopd|filer|continuous|Filer_File_Manager-*-x86_64.AppImage.zsync
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: GPL-2.0
---