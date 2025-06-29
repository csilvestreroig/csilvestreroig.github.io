---
layout: default
---
# My Projects

<ul>
{% for p in site.projects %}
  <li><a href="{{ p.url }}">{{ p.title }}</a> — {{ p.description }}</li>
{% endfor %}
</ul>
