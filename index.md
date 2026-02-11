---
layout: default
title: "Kiire blogi"
---

# Tere!

Siin on minu postitused:

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date: "%d.%m.%Y" }}
  </li>
{% endfor %}
</ul>
