--- 
code: 
  - |-
      //EN: Moving object along axes is fun
      //    now even more so
      //RU: Двигать объекты по осям весело
      //    теперь немножко веселее
      return argument0 * (keyboard_check(argument2)-keyboard_check(argument1));
date: 2014-02-14 16:00:00
layout: post
tags: 
  - wtf
  - one line
  - controls
title: axis_move
arguments: (speed, minus, plus)
author: <code>D-side</code> <a class="btn btn-xs btn-primary" href="https://vk.com/d.side"><i class="icon-vk"></i></a><a class="btn btn-xs btn-info" href="http://dside.ru"><i class="icon-globe"></i></a><a class="btn btn-xs btn-danger" href="http://blog.dside.ru"><i class="icon-edit"></i></a>
---

{% highlight c %}
{{ page.code[0] }}
{% endhighlight %}

{% highlight c %}
// RU: многие делают примерно так каждый шаг:
// EN: most do something like this every step:
x += {{page.title}}(4, vk_left, vk_right);
y += {{page.title}}(4, vk_up, vk_down);
{% endhighlight %}
