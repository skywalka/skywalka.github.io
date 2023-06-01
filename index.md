---
layout: default
---

[About](./about).

# Securitah FTW

Welcome to the number one securitah blog on the internets.

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
