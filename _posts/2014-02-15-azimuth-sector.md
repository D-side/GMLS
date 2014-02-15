--- 
code: 
  - |-
      var d0,d1,d;
      
      d0 = ((argument0 mod 360) + 360) mod 360;
      d1 = ((argument1 mod 360) + 360) mod 360;
      d = ((argument2 mod 360) + 360) mod 360;
      return (((d1-d0)>0) xor ((d<d0) xor (d>=d1)));
      
      //EN: This code checks the position of azimuth - d with respect to the sector d0,d1
      //RU: Этот код проверяет положение азимута - d относительно сектора d0,d1

date: 2014-02-15 21:24:00
layout: post
tags: 
  - direction
  - math
title: direction_in_sector
arguments: (d0, d1, d)
author: <a class="btn btn-xs btn-primary" href="https://vk.com/rustam_azizov"><i class="icon-vk">/</i>rustam_azizov</a>

---

{% highlight c %}
{{ page.code[0] }}
{% endhighlight %}
