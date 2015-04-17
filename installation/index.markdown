---
layout: jasonlong
title: "Installation"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
menu: /installation Installation
published: true
---

#### ContentNinja installieren.

Das Git Repository klonen:

    git clone https://github.com/contentninjaservices/contentninja.git

#### oder das [ZIP-File](https://github.com/contentninjaservices/contentninja/archive/master.zip) herunterladen

    unzip master.zip

#### Installtion mit Homebrew am Mac 

    brew install https://raw.githubusercontent.com/contentninjaservices/homebrew/master/contentninja.rb

#### Ins Verzeichnis wechseln 

    cd ContentNinja-master 
    

#### Deine Seite generieren

    perl contentninja.pl 

Das ist alles  :-) 

#### Konfiguration Step by Step

[lese](/configuration) Seiten zur Konfiguration von ContentNinja..

#### Verzeichnis- und Dateiübersicht

    |____contentninja.pl
    |____lib
    | |____SPP.pm
    |____LICENSE
    |____Makefile
    |____Modules
    | |____Codeblock.pm
    | |____Gallery.pm
    | |____Includecode.pm
    | |____Youtube.pm
    |____themes
    | |____jasonlong
    | | |_____includes
    | | | |____configuration
    | | | | |____navigation.html
    | | | |____footer.html
    | | | |____jasonlong.html
    | | | |____navigation.html
    | | |_____layout
    | | | |____fixissue3
    | | | |____jasonlong.html
    | | |____themefiles
    | | | |____fancybox
    | | | | |____lib
    | | | | | |____jquery-1.10.1.min.js
    | | | | | |____jquery-1.9.0.min.js
    | | | | | |____jquery.mousewheel-3.0.6.pack.js
    | | | | |____source
    | | | | | |____blank.gif
    | | | | | |____fancybox_loading.gif
    | | | | | |____fancybox_loading@2x.gif
    | | | | | |____fancybox_overlay.png
    | | | | | |____fancybox_sprite.png
    | | | | | |____fancybox_sprite@2x.png
    | | | | | |____helpers
    | | | | | | |____fancybox_buttons.png
    | | | | | | |____jquery.fancybox-buttons.css
    | | | | | | |____jquery.fancybox-buttons.js
    | | | | | | |____jquery.fancybox-media.js
    | | | | | | |____jquery.fancybox-thumbs.css
    | | | | | | |____jquery.fancybox-thumbs.js
    | | | | | |____jquery.fancybox.css
    | | | | | |____jquery.fancybox.js
    | | | | | |____jquery.fancybox.pack.js
    | | | |____images
    | | | | |____body-bg.png
    | | | | |____highlight-bg.jpg
    | | | | |____hr.png
    | | | | |____ninja.png
    | | | | |____octocat-icon.png
    | | | | |____sidebar_hr.png
    | | | | |____tar-gz-icon.png
    | | | | |____zip-icon.png
    | | | |____js
    | | | | |____jquery.min.js
    | | | |____stylesheets
    | | | | |____print.css
    | | | | |____pygment_trac.css
    | | | | |____screen.css
    | | | | |____stylesheet.css

