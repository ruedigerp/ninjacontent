---
layout: jasonlong
title: "Examples"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
menu: /examples/ Examples
published: true
---

### Header

{% includecode 1:examples/header.code %}

*Result:*

# H1
## H2
### H3
#### H4
##### H5
###### H6

### Bold and underline 

{% includecode 2:examples/bold.code %}

*Result:*

Here is *bold* text. 
And now _underlined_ test.

### Codeblock

{% includecode 3:examples/codeblock.code %}

*Result:*

{% codeblock %}
{% gallery %}
edimaxew7811.jpg: wlan stuff
Pi1.png: Raspberry stuff
{% endgallery %}
{% endcodeblock %}

### Include code from file

{% includecode 4:examples/includecode.code %}

*Result:*

{% includecode 5:examples/includecode2.code %}

### List 

{% includecode 6:examples/list.code %}

*Result:*

  * one
  * two
  * three

### Gallery 

{% includecode 7:examples/gallery.code %}

*Result:*

{% gallery %}
/gallery/15783866983_27160395b9_b.jpg: Rodeo Dusk (_JonathanMitchellPhotography_)
/gallery/10346743894_0cfda8ff7a_b.jpg: Les papillons ont du chagrin (JMS')
/gallery/14395875498_c43e5c4415_b.jpg: Chedder Gorge with goats looking (Si Photography)
/gallery/15723733583_b4a7b52459_b.jpg: Pudacuo (OsvinC)
{% endgallery %}


##### View sourcecode of this site

[sourcecode](/examples/indexcode.html)



