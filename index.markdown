---
layout: default
title: "Home"
---
<ul>
{% for post in site.posts %}
  <li class="post">
    <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
  </li>
{% endfor %}
</ul>

