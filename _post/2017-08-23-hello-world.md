---
layout: post
title: "Welcome to jekyll"
---

this is a thing

<ul>
 {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
