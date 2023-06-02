---
layout: default
---

[About](./about).

![alt text](/images/boogie-down-productions-criminal-minded.jpg "Criminal minded, you've been blinded"){: height="250" }

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
