---
layout: jasonlong
title: "Deiner erste Seite"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
published: true
---

{% include configuration/navigation.html %}

## Erstelle eine Datei für die erste Seite. 

Erstelle ein Verzeichnis "source" und da drin eine Datei "index.markdown" mit folgenden Inhalt: 

{% includecode 1:configuration/firstpage.code %}

Der erste Teile zwischen den beiden "---" ist der Kopf einer Datei. Er enthält Daten wie Tile, Datum usw. 

Mit dem Parameter `layout` wird das benutzte Layout ausgewählt. Das Layout ist gespeichert in "theme/YourTheme/\_layout".
Mehr dazu später.

Der Parameter `published` kann auf `true` oder `false` gesetzt werden. Fügt man neue Seiten hinzu, kann man die erst einmal auf `false` satzen. Dann werden sie beim neugenerieren der Internetseite nicht erstellt. Kann dazu benutzt werden wenn Texte noch nicht fertig sind oder erst noch korrektur gelesen werden sollen. 

Muss man in einem Text nach der Veröffentlichung einen Fehler beseitigen und die einzelne Seite soll in dieser Zeit nicht online sein, kann man einfach `published: false` setzen. 

Der Parameter `profile` meint das Google+ Profile des Autors der Seite. Im Layout wird es mit dem Autor des Inhalts verknüpft. In den Google Suchergebnissen wird dann das Profilbild des Google+ Profiles angezeigt. 

Alle anderen Parameter im Kopfbereich erklären sich selbst und werden nicht weiter beschrieben. 

Der Bereich mit dem Inhalt wird später beschrieben. Dann werden auch die Formatierungsmöglichkeiten mit Markdown beschrieben. 

Nächster Schritt ist das [Layout](/configuration/layout.html).

