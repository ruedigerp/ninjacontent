---
layout: jasonlong
title: "Konfiguration"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
menu: /configuration Configuration
published: true
---

{% include configuration/navigation.html %}

## Configuration file

Das ContentNinja Konfigurationsdatei heisst: ninja.config.

    remoteurl = http://www.example.com
    localurl = http://localhost
    
		sitelogo = /images/sitelogo.png
    sitetitle = Page Title
    siteauthor = John Smith
    siteemail = mail@example.com
    siteurl = http://www.example.com
    
    default_index = source/index.markdown
    comtec = 1
    
    bin	= /Users/rpr/bin
    lib	= /Users/rpr/bin/lib
    
    source = source
    posts	=	_posts
    drafts = _drafts
    stash	= _stash
    public = output
    
    theme = jasonlong
    
    debug = 0


## Detail information for the configfile

Einige Paramter im Konfigurationfile werden aktuell nicht benutzt.
ContentNinja wurde als Blogging-Software erstellt. 
Der Teil für das Bloggen wurde entfernt, so das sich ContentNinja aktuell nur um das erstellen von Internetseiten kümmert. 
Die Funktionen für das Bloggen werden aber später wieder hinzugefügt. 

Die folgenden Parameter werden aktuell nicht benutzt:

   * post.title post.content
   * comtec
   * bin
   * lib 
   * posts
   * drafts
   * stash


### remoteurl

    remoteurl = http://www.example.com

ContentNinja kann die fertigen Seiten auf einen Server per ssh oder rsync kopieren. 
Die kann zum Beispiel benutzt werden, wenn man die Seite erst auf test.domainname.de testen möchte
und nach einem Test erst für alle unter www.domainname.de erreichbar machen möchte. 
Dadurch werden die Links auf der Internetseite passend für die Test und Live Internetseite gesetzt.

### localurl

    localurl = http://localhost

ContentNinja kann die fertigen Seiten auf einen Server per ssh oder rsync kopieren. 
Die kann zum Beispiel benutzt werden, wenn man die Seite erst auf test.domainname.de testen möchte
und nach einem Test erst für alle unter www.domainname.de erreichbar machen möchte. 
Dadurch werden die Links auf der Internetseite passend für die Test und Live Internetseite gesetzt.

### site.title 

    sitetitle = Page Title

Setzt den Seitentitel im Kopfbereich der Internetseite. Kann im Template ersetzt werden mit: 

Template: 

    {% sitetitle %}

### site.title 

    sitesubtitle = Subtitle

Setzt den Seitenuntertitel im Kopfbereich der Internetseite. Kann im Template ersetzt werden mit: 

Template: 

    {% sitesubtitle %}

### site.author 

    siteauthor = John Smith

Setzt den Author im Kopfbereich der Internetseite. Kann im Template ersetzt werden mit: 

Template: 

    {% siteauthor %}

### site.email

    siteemail = mail@example.com

Setzt die E-Mailadresse im Kopfbereich der Internetseite. Kann im Template ersetzt werden mit: 

Template: 

    {% siteemail %}

### post.title post.content

Unbenutzt, wird von der Blog-Engine benutzt

### siteurl 

    siteurl = http://www.example.com

Setzt die Seiten URL in den Sietenkopf und kann im Template setzte werden mit: 

Template: 

    {% siteurl %}

### default_index 

    default_index = source/index.markdown

Die standard Seite. Diese Seite wird den Besuchern gezeigt wenn sie die Internetsiete aufrufen.

Ist aktuell nicht benutzt und wird in einer zukünftigen Version wieder aktiviert.

### comtec 

    comtac = 0|1 

comtec steht für: CommentTec, ein Kommentarsystem für ContentNinja. 
ContentNinja generiert statische Internetseiten und kann keine dynamischen Inhalte bearbeiten. 
Kommentare können aber mit Hilfe von z.B. Disqus.com ermöglicht werden.
ComTec ist dann entstanden um die Daten der Besucher nicht auf Servern anderer Anbieter zu speichern.
Die Daten bleiben mit ComTec auf dem eigenen Server. 
Die Besucher können dann auch nicht von anderen Anbietern getracked werden. 
Und die Daten liegen auch nicht auf den Servern eines Anbieters im Ausland. 

ComTec wird unabhängig von ContentNinja entwickelt. ComTec kann somit auch mit anderen Blogsystemen benutzt werden.
In Zukunft wird ComTec auch veröffentlicht, wann genau kann aber noch nicht gesagt werden.

### bin	

Unbenutzt. 

    bin = /path/to/bin

### lib	

Unbenutzt. 

    lib = /path/to/lib 

### source 

This directory contains a javascript, stylesheet, your pages etc.
Dieses Verzeichnis enthält die Inhalte der Seite (Markdowndateien), Javascripte, CSS-Stylesheets.
Für weitere Informationen bitte die DoKumentation lesen. Abschnitt: "Deine erste Seite" und folgende. 

    source = source 

### posts	

Unbenutzt. Blog Engine :) 

    posts = _posts 

### drafts 

Unbenutzt. Blog Engine :) 

    drafts = _drafts

### stash	

Unbenutzt. Blog Engine :) 

    stash	= _stash

### theme

Wählt ein instaliertes Layout aus. 

    theme = jasonlong


### debug 

if debug = 1 is set to debug issues when generating pages.
Wenn debug=1 gesetzt ist, werden Fehler ausgeben beim generieren. 

Aktuell werden nur Laufzeitmeldungen ausgegben um die Zeit einzelner Steps beim generieren auszugeben. 
Wer ein eigenes Modul schreibt sollte debug auf 1 setzen beim testen. 

    debug = 0|1


