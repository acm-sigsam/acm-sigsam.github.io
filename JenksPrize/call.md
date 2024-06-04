---
layout: default
---
<center>
  <h2> 
    Richard Dimick Jenks <br>
    Memorial Prize for Excellence in <br>
    Software Engineering applied to Computer Algebra
  </h2>
  <h3> Call for nominations  </h3>

</center>
 
  {% assign sorted = site.awards_jenks_calls | sort: 'year' | reverse %}
 
 {{ sorted.first.content }}