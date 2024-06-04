---
layout: default
permalink: /ISSACawards
---
<center>
  <h1> 
   ISSAC Awards
  </h1>
</center>
 
 SIGSAM sponsors awards for
- Distinguished Papers and 
- Distinguished Student Authors 
at the annual [International Symposium on Symbolic and Algebraic Computation (ISSAC)](https://www.issac-conference.org/).

The [award guidelines are available here]({{site.baseurl}}/{{item.url}}ISSACawards/guidelines).

If you have any corrections or can fill in any missing information please contact the [Information Director](mailto:Infodir_SIGSAM@acm.org).

{% assign current_year =   site.time | date: '%Y'   %}


 


{% for year in (2002..current_year) reversed %}
<h3>ISSAC {{ year }}</h3>
{% for award in site.awards_issac_best_paper %}
{% if award.year == year %}
<div class="col-md-12" style="border:solid">
<b>Distinguished Paper award</b>
<br>
<a href="{{ award.doi }}">{{ award.title }}</a>
<br>
<ul>
{% assign authors = award.authors | split: "," %}
{% for author in authors %}
 <li>{{ author }}</li>
{% endfor %}
</ul>
</div>
 {% endif %}
{% endfor %}
  

{% endfor %}
 



