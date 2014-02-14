--- 
code: 
  - |-
      //EN: I heard YoYo are adding data accessors for maps
      //    So it's sort of obsolete.
      //RU: Слышал, YoYo добавляют для мапов особые операции
      //    Возможно, это уже и не понадобится
      if (ds_map_exists(argument0,argument1))
        ds_map_delete(argument0,argument1);
      ds_map_add(argument0,argument1,argument2);
date: 2014-02-09 17:00:00
layout: post
tags: 
  - data structures
title: ds_map_emplace
arguments: (map, key, value)
author: <a class="btn btn-xs btn-primary" href="https://vk.com/grindcoreopera"><i class="icon-vk">/</i>grindcoreopera</a>
---

{% highlight c %}
{{ page.code[0] }}
{% endhighlight %}
