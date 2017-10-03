# Nützliches und Helferlein für Developer

- [Beschreibung](#beschreibung)
- [Nützliche AddOns](#addons)
  - [Cheatsheat für Extensionpoints](#cheatsheet)
  - [Developer - Module, Templates und Aktionen syncen](#developer)
  - [YTraduko - Übersetzungshelfer](#ytraduko)
  - [ZIP-Install](#zip)
- [Software und Workflows](#swork)
  - [REDAXO mit Bimmelbam](#bimmelbam)
  - [REDAXO mit Docker](#docker)
- [Nützliche Links](#)

<a name="beschreibung"></a>
## Beschreibung

Nachfolgend listen wir hier nützliche Informationen, AddOns und Links, die die Entwicklung eines AddOns oder des geplanten Projektes erleichtern. Wer mitmachen möchte, sendet bitte seine Ergänzungen als PR. 

<a name="addons"></a>
## AddOns

<a name="addons"></a>
### Cheatsheet

Das Cheatsheet-AddOn scant die REDAXO-Installation nach Extension-Points im Core und den installierten AddOns und listet deren Position im Quellcode auf. 

**Installation aus Github-Repo:** https://github.com/tbaddade/redaxo_cheatsheet

<a name="developer"></a>
### Developer

Developer kopiert und synct Module, Templates und Aktionen zwischen Dateisystem und Datenbank, so werden diese leicht für externe Editoren und per FTP zugänglich.

**Installation per Installer**

**Github-Repo:** https://github.com/FriendsOfREDAXO/developer

<a name="ytraduko"></a>
### YTraduko - Übersetzungshelfer 

Ytraduko hilft bei der Übersetzung der eigenen AddOns. Anstelle selbst für die weiteren Sprachen neue .lang - Dateien anzulegen, erledigt dieses AddOn es selbst. Die Übersetzungen können übersichtlich und schnell eingepflegt werden. 

**Installation aus Github-Repo:** https://github.com/yakamara/ytraduko

<a name="zip"></a>
### ZIP-Install 

Das ZIP-Install ermöglicht es gezippte AddOns ohne Umweg per FTP auf den Server zu laden und zu entpacken. Ganz praktisch vor allem, wenn es sich um AddOns handelt, die es nur als GitHub-Repo gibt und nicht im Installer zur Vefügung stehen.  

**Installation per Installer**

**GitHub-Repo:** https://github.com/FriendsOfREDAXO/zip_install


## Software und Workflows

<a name="bimmelbam"></a>
### REDAXO mit Gulp, Browserify, PostCSS und Bimmelbam

Ein Frontend-Workflow auch für REDAXO

Frontendentwicklung wird immer aufwändiger, SCSS wollen kompiliert werden, Bilder komprimiert werden, JS schöner werde, HTML-Prootypen wollen erzeugt werden. ***REDAXO mit Bimmelbam*** zeigt hierfür einen ausbaufähigen Weg. 

**GitHub-Repo:** https://github.com/FriendsOfREDAXO/redaxo-mit-bimmelbam


<a name="docker"></a>
### REDAXO mit Docker

***MAMP und XAMP waren gestern!*** REDAXO kann leicht systemunabhängig mit Docker verwendet werden. Die Vorteile: Möglichkeit der zentralen Installation und Bearbeitung, Versionierbarkeit, Ausbaufähigkeit. REDAXO-mit-Docker liefert alle Ressourcen und eine einsteigergeignete Anleitung. Und damit man nicht bei Null anfangen muss, kann eine Demo gleich automatisiert installiert werden. ***REDAXO mit Docker und Bimmelbam*** sind übrigens leicht miteinander kombinierbar. Weiter Infos in den jeweiligen REPOS. 

**GitHub-Repo:** https://github.com/FriendsOfREDAXO/redaxo-mit-docker