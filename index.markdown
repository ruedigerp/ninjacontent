---
layout: default
title: "ContentNinja"
date: 2015-04-11 00:00:00
comtec: 20115-04-11
comments: false
author: John Smith
profile: 107224552229621877852
menu: / Startseite
image: 
categories: 
  - categorie1
tags:
  - tag1
  - tag2
published: true
---

#### Erstelle einfach statische Internetseiten. 

Internetseiten mit Markdown erstellen, generieren und auf einen oder mehrere Server kopieren. 
Der Server benötigt kein PHP, Perl, ASP.net, Python usw. und auch keine Datenbank wie MySQL, PostgreSQL oder MSSQL. 

#### Worum ContentNinja?

Viele Leute wollen eine Internetseite haben und haben keine Ahnung wie die ganze Software auf einem Server funktionieren. 
Wieso sollten sie? Sie wollen nur eine Internetseite. 
Sie fragen jemanden der sich angeblich damit auskennt. Und erhalten dann: 

Ask someone which knows a little about it. The result is:

	* Webspace, der viel zu gross ist. 
	* Mit PHP, Perl, Python usw. 
	* Datenbanken, mit denen sie sich nicht auskennen. 
	* Oder einen Server, der einfach überdimensioniert ist. 

Anschliessend wird WordPress, Joomla, Typo3 oder ein anderen Content Management System installiert. 
Die Systeme sehen nie ein Update und werden Ziel von Angreifern. Oft wird ein ungepflegtes System für weitere Attacken auf andere Server ausgenutzt.

Anstatt einen Server für 30,- könnte man für die gleiche Summe auch 3-4 kleinere Server bekommen. 
Mit ContentNinja erstellte Seiten können dann einfach auf mehrere Server kopiert werden. 
Die Last wird auf mehrere Server verteilt. Fällt einer aus bleibt die Seite online. 

Man kann: 

  * Einen Server aktualisieren ohne das die Seite offline ist.
  * Einen Server austauschen, ohne das die Seite offline ist..

Wird ContentNinj zusammen mit Subversion oder GIT benutzt, kann man zu schnell zu alten Versionen einer Seite zurück wechseln. 
Oder man erstellt einen so genannten "Branch" und erstellt ein neues Layout. So kann man ein neues Layout testen ohne die aktuelle Seite im Intenet zu beeinflussen. 
Ist man fertig wendet man die neue Version einfach auf die Seite im Internet an. Hat man einen Fehler gemacht geht man einfach wieder auf die alte Version zurück.


#### Eine Datei pro Seite. 

A page in a file has a header and the content.
Eine Page in einer Datei besteht aus einem "Header" (Kopf) und dem "Body" (Inhalt der Seite).


##### Header

    ---
    layout: default
    title: "Content Nija"
    date: 2015-04-11 00:00:00
    author: John Smith
    published: true
    ---

##### Body 


    ### Die ist eine Überschrift Grösse 3
		
    Hier ist ein Absatz mit einen Beispiel Text. 
    
		Hier ist ein Absatz mit weiteren Text. 
    
    #### This is a H4 header 


##### ContentNinja herunterladen oder als SaaS online benutzen.

ContentNinja wird bald auch als SaaS (Software as a Service) online verfpgbar sein. 
Dadurch entfällt dann der Download und die Markdown Dateien der Internetseite können z.B. per GIT bei github.com gespeichert werden. 
Layout auswählen, URL vom Repository auf github.com eintragen und auf generieren klicken. 
ContentNinja generiert anschliessend die Internetseite und stellt diese zur Verfügung. 

Die fertige Seite kann dann angeguckt werden. Wenn alles ok ist herunterladen und auf den eigenen Webspace kopieren. 

ContentNinja SaaS ist aktuell schon fertig und generiert regelmässig diese Seiten hier neu. 
Um ContentNInja SaaS allen zur Verfügung stellen zu können fehlen aktuell nur noch ein paar Designs zur Auswahl. 

Weiter ist in Zukunft auch noch geplant das kopieren auf den eigenen Webspace auch noch mit anzubieten. 
Dann muss man sich nur noch um die Inhalte können, das generieren und im Internet verfügbar machen übernimmt dann ContentNinja SaaS komplett. 

#### Inatallation und Konfiguration

Anleitung für die Installation und Konfiguration ist [hier](/installation/) zu finden.


