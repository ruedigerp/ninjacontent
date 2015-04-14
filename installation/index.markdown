---
layout: jasonlong
title: "Installation"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
published: true
---

#### Content Ninja installation

Clone the git repository:

    git clone git@github.com:ruedigerp/ContentNinja.git

or download the [ZIP-File](https://github.com/ruedigerp/ContentNinja/archive/master.zip) 

    unzip master.zip

Change to the directory Content Ninja

    cd ContentNinja-master 
    

#### Generate your first Page

    perl contentninja.pl 

that's all. :-) 

#### Configuration step by step 

[Read](/configuration) the configuration pages.


#### Directory and file overview

    |____CHANGELOG.md
    |____contentninja.pl
    |____lib
    | |____SPP.pm
    |____LICENSE
    |____Modules
    | |____Codeblock.pm
    | |____Gallery.pm
    | |____Youtube.pm
    |____README.md
    |____themes
    | |____jasonlong
    | | |_____includes
    | | | |____footer.html
    | | | |____jasonlong.html
    | | |_____layout
    | | | |____jasonlong.html
    | | |____themefiles
    | | | |____images
    | | | | |____body-bg.png
    | | | | |____highlight-bg.jpg
    | | | | |____hr.png
    | | | | |____ninja.png
    | | | | |____octocat-icon.png
    | | | | |____sidebar_hr.png
    | | | | |____tar-gz-icon.png
    | | | | |____zip-icon.png
    | | | |____stylesheets
    | | | | |____print.css
    | | | | |____pygment_trac.css
    | | | | |____screen.css
    | | | | |____stylesheet.css


#### Content directory "source"

Example directory structure for a test homepage:

    |____about
    | |____index.markdown
    | |____impressum.markdown
    | |____team.markdown
    |____download
    | |____index.markdown
    |____index.markdown
    |____gallery
    | |____index.markdown
    |____ninja.config



