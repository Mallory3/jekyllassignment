---
layout: wrapper
title: Collection
permalink: /collection/
---

<!-- https://www.youtube.com/watch?v=o7ygmIRgvUA -->

<div id="blogListSection">
  <div id="collectionHero"></div>

<div id="blogListBackground">
<h2 id="blogTitle">Sample Collection Posts</h2>
    <ul>
      {% for birdy in site.birds %}
  <li class="birdy" id="blogList">
    <a class="button" href="{{ birdy.url }}">
      <div>{{ birdy.title}}</div>
      <div>{{ birdy.title}}</div>
    </a>
  </li>
      {% endfor %}
    </ul>
</div>