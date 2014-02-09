--- 
category: wtf
code: 
  - |-
      //Since there are no bools in GML
      //Numbers 0 and 1 have to act in their place
      return (argument0 < argument1) * argument0 + (argument0 >= argument1) * argument1;
date: 2014-02-09
layout: post
tags: 
  - wtf
  - math
title: wtf_min
arguments: (a, b)
author: <a class="btn btn-sm btn-primary" href="https://vk.com/rustam_azizov"><i class="icon-vk">/</i>rustam_azizov</a>
---

{% highlight c %}
  {{ page.code[0] }}
{% endhighlight %}
