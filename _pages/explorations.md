---
layout: single
author_profile: false
permalink: "/Explorations/"
sidebar:
   nav: "explorations"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>