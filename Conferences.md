---
layout: base
title: Conferences
---                
             
{% for item in site.conferences %}
    {{ item.title }}  ({{item.city}}, {{item.country}} )
    [conference website]({{item.website}})
{% endfor %}       

 
