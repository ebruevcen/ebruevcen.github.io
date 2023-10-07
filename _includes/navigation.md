---
layout: default
---

{% for link in site.data.navigation %}
  {% if link.right %}
    <a class="normal right" href="{{ link.url }}">{{ link.title }}</a>
  {% else %}
    <a class="normal" href="{{ link.url }}">{{ link.title }}</a>
  {% endif %}
{% endfor %}
