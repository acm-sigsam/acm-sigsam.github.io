---
layout: base
title: Journals
---

 
{% for journal in site.journals %}

  <div class="row">
      <h3><strong> {{journal.title}} ({{journal.abbreviation}}) </strong> </h3>

      <div class="col-md-3">
          <img src="{{site.baseurl}}/assets/images/covers/journals/{{journal.cover}}" alt="Picture"> 
      </div>
      <div class="col-md-6">
          <p><a href="{{journal.website}}" target="_blank">Journal website</a></p>
          <p>Publisher: {{journal.publisher}}</p>
          <p> Editor-in-Chief: {{journal.editor}} </p>
          <a href="{{journal.board}}" target="_blank"> Editorial Board </a> <br>
      </div>
  </div>

{% endfor %}

 
 