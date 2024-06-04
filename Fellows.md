---
layout: base
---
ACM Fellows from our community


{% for fellow in site.fellows %} 
   {{fellow.fellow_name}} ({{fellow.year}})<br>
     {{fellow.citation}}
     <br><br>
     <!-- {{fellow.link}}  
     <br>
     <br> -->
{% endfor %}

