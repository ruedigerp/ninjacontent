---
layout: jasonlong
title: "Layout files"
date: 2015-04-11 00:00:00
author: John Smith
profile: 107224552229621877852
published: true
---

{% include configuration/navigation.html %}

## The layout files

The layout files are in the directory "theme/yourtheme/_layout". Here is an example "default.html":
    
{% includecode 1:configuration/layout.code %}


### Includes 

In the first row of the HTML header is loaded via include. This includes are located in the directory "theme/yourtheme/_include". Includes can load other includes.
In head.html will include, for example, "theme/yourtheme/themefiles/css/screen.css". The "css/screen.css" is also stored in the directory "theme/yourtheme/_include".

Furthermore, code in default.html normal HTML. In between is still a inlude the navigation area of the page.

In the section "your first page" when a header file Markdown for Content Ninja is described. 

### Replace content and other variables

The second part is the content part of a page. The part that is visible on the page later.
This area will be inserted here. And is at the location of the { % content %}.

### The layout from pages

Includes also be used for the layout of content. In the header of a page is the parameter "layout: default.html". This file is loaded from the include folder.

Here layout of our content areas:

{% includecode 2:configuration/contentarea.code %}


This part is currently still a little confusing. Internal are the two variables "content" used. 
When you generate a page is the content of a page loaded in content and then replaced in the include directory for layout instead of content.
The result is stored. But then inserted in the entire page layout and content also means again. 
That will change in a future version and then makes it easier to understand.




