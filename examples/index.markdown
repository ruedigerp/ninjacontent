---
layout: jasonlong
title: "Beispiele"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
menu: /examples/ Beispiele
published: true
---

### Überschriften

{% includecode 1:examples/header.code %}

*Ergenis:*

# H1
## H2
### H3
#### H4
##### H5
###### H6

### Fett und unterstrichen 

{% includecode 2:examples/bold.code %}

*Ergebnis:*

Hier ist *fetter* Text. 
And nun _unterstrichener_ Text.

### Codeblock

{% includecode 3:examples/codeblock.code %}

*Ergebnis:*

{% codeblock %}
{% gallery %}
edimaxew7811.jpg: wlan stuff
Pi1.png: Raspberry stuff
{% endgallery %}
{% endcodeblock %}

### Code aus Datei einfügen

{% includecode 4:examples/includecode.code %}

*Ergebnis:*

{% includecode 5:examples/includecode2.code %}

### Listen 

{% includecode 6:examples/list.code %}

*Ergebnis:*

  * one
  * two
  * three

### Gallerie

{% includecode 7:examples/gallery.code %}

*Ergebnis:*

{% gallery %}
/gallery/15783866983_27160395b9_b.jpg: Rodeo Dusk (_JonathanMitchellPhotography_)
/gallery/10346743894_0cfda8ff7a_b.jpg: Les papillons ont du chagrin (JMS')
/gallery/14395875498_c43e5c4415_b.jpg: Chedder Gorge with goats looking (Si Photography)
/gallery/15723733583_b4a7b52459_b.jpg: Pudacuo (OsvinC)
{% endgallery %}

### Youtube video

{% includecode 8:examples/youtube.code %}

*Ergebnis:*

{% youtube 4tzhyfWHdLo %}

### Links

{% includecode 9:examples/links.code %}

*Ergebnis:*

[ContentNinja](http://contentninja.services) and [ContentNinja Saas](http://saas.contentninja.services)

or: 

Here are some links to other pages. [ContentNinja] [1] and [ContentNinja Saas] [2]

  [1]: http://contentninja.services        "ContentNinja"
  [2]: http://saas.contentninja.services   "Saas"


##### Den Code dieser Seite angucken

[sourcecode](/examples/indexcode.html)



