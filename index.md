---
layout: default
title: Zhenzhen Qi
---
<section id="pages">
  <li><a href="{{ '/about/' | relative_url }}">About / CV</a></li>
  <li class="mobile-only"><a href="#project-list-anchor">Projects</a></li>
</section>

<header>
  <nav class="navbar">
    <ul><li><a class="active" href="{{ '/' | relative_url }}">Zhenzhen Qi</a></li></ul>
  </nav>
</header>

<div class="row">
  <div class="col" id="left">
    {% include project-list.html %}
  </div>
  <div class="col" id="center">
    <div id="content">
      <h1 class="sr-only">Zhenzhen Qi — artist, educator, and creative technologist in New York.</h1>
      <br><br><br><br>
    </div>
    <div class="mobile-only" id="project-list-anchor">
      <hr>
      <div class="mobile-project-heading">PROJECT LIST:</div>
      {% include project-list.html %}
    </div>
  </div>
  <div class="col" id="right"></div>
</div>
