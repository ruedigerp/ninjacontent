---
layout: jasonlong
title: "Layout Dateien"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
published: true
---

{% include configuration/navigation.html %}

## Die Layout Dateien

Die Layout Dateien sind im Verzeichnis "theme/DeinLayout/\_layout" gespeichert. 
Hier ist als Beispiel die Datei "default.html": 

{% includecode 1:configuration/layout.code %}


### Includes 

In dem Beispiel oben wird in der ersten Zeile ein Include benutzt. Includes werden asu dem Verzeichnis "theme/yourtheme/\_include" eingelesen.
Includes können weitere Includes einfügen. 

In der Datei "head.html" wird dann zum Beipspiel eine weitere Datei hinzugefügt. 

Zusätzlich wird in der Datei "head.html" noch die Navigation der Seite geladen. 

Im Abschnitt "Deine erste Seite" wird der Inhalt einer ContentNinja Markdown Datei beschrieben. 

### Replace content and other variables

Der zweite Teil in einer Markdown Datei ist der Bereich für den Inhalt einer Seite. 
Also der Teil, den Besucher nachher auf der Internetseite sehen. 
Im Layout wird dieser Bereich eingesetzt. Ersetzt damit die Variable "content".
Im Layout wird diese Variable mit `{% content %}` benutzt. 

### Das Layout fon Seiten

Includes können also dazu benutzt werden um das Layout der Seite zu steuern. 
Im Kopf der Datei gibt es den Parameter "layout". Zum Beispiel "layout: default.html" und wird aus dem Ordner "theme/yourtheme/\_include" geladen.

Im Standardlayout wird in "default.html" der eigentliche Bereich für die Inhalte in einer extra Datei ausgelagert. 
Um in zu laden wird das oben erwähnte Inlude benutzt. 

Hier der eigentlich Contentbereich als Beispiel: 

{% includecode 2:configuration/contentarea.code %}




