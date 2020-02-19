---
layout: default
---

# List of Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <i>{{ post.date | date: "%B %-d %Y" }}</i>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>