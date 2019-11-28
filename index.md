---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: wrapper
title: Blog
permalink: /blog/
---


<div id="blogListSection">
  <div id="blogHero"></div>

<div id="blogListBackground">
<h2 id="blogTitle">Sample Blog Posts</h2>
    <ul>
      {% for post in site.posts %}
  <li id="blogList">
    <a class="button" href="{{ post.url }}">
      <div>{{ post.title}}</div>
      <div>{{ post.title}}</div>
    </a>
  </li>
      {% endfor %}
    </ul>
</div>