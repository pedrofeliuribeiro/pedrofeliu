---
layout: default
author_profile: false
---

<div id="main" role="main">
  {% include sidebar.html %}
h1>Prof. Pedro Feliú Ribeiro</h1>
	<p>I am an Associated Professor at the International Relations Institute of the University of São Paulo, Brazil. I research issues related to Foreign Policy Analysis and Legislative Studies  with a focus on Latin American countries.</p>
  <div class="archive">
    <h1 class="page__title">{{ page.title }}</h1>
    {% include base_path %}
    {% for post in page.posts %}
      {% include archive-single.html %}
    {% endfor %}
  </div>
</div>
