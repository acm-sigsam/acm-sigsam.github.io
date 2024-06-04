---
layout: default
---
<center>
  <h1> 
    Richard Dimick Jenks <br>
    Memorial Prize for Excellence in <br>
    Software Engineering applied to Computer Algebra
  </h1>
</center>
 
![Dick Jenks (1937 -- 2003)]({{site.url}}/{{site.baseurl}}/assets/images/people/jenks.jpg)

<center><h2>Dick Jenks (1937 -- 2003)</h2></center>


<p>
The purpose of the Jenks Memorial Prize is to recognize outstanding software engineering contributions in the field of computer algebra and to encourage future excellence in such research and development. The prize is named in memory of Richard Dimick Jenks who, during his life and professional career, provided leadership to the computer algebra community and made important contributions to software engineering applied to algebraic computation. The prize will be awarded bi-annually in even numbered years. The first prize was awarded in 2004. Henceforth, a competition will be carried out every other year.
</p>

As of the Summer of 2006, the prize is now officially named the ACM SIGSAM Richard Dimick Jenks Memorial Prize.

You can find information [about the origin and administration of the prize]({{site.baseurl}}/{{item.url}}JenksPrize/origin) or the [procedures of nomination and selection]({{site.baseurl}}/{{item.url}}JenksPrize/procedures).

The call for nominations is [available here]({{site.baseurl}}/{{item.url}}JenksPrize/call)

<div>
<h2>Jenks Prize Laureates</h2>
  {% for item in  site.awards_jenks  %}
        <a href="{{site.baseurl}}{{item.url}}" >{{item.year}} - {{item.awardee}}</a>
        
        <br><br>
  {% endfor %}
</div>
 