---
layout: jasonlong
title: "Example: Codeblock"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
menu: /examples/codeblock.html Codeblock
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

