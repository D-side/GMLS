--- 
code: 
  - |-
      //EN: Since there are no booleans in GML
      //    Numbers 0 and 1 have to act in their place
      //RU: Ну нет в GML логического типа
      //    вот цифры 0 и 1 за него и отдуваются.
      return (argument0 < argument1) * argument0 + (argument0 >= argument1) * argument1;
date: 2014-02-09 16:00:00
layout: post
tags: 
  - wtf
  - math
  - one line
title: wtf_min
arguments: (a, b)
author: <a class="btn btn-xs btn-primary" href="https://vk.com/rustam_azizov"><i class="icon-vk">/</i>rustam_azizov</a>
---

{% highlight c %}
{{ page.code[0] }}
{% endhighlight %}
