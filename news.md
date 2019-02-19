---
layout: default
---

# News

{% for post in site.posts %}
  [{{ post.title }}]({{ post.url }})<br /><small>{{ post.date | date: "%B %d, %Y" }}</small><br />
  {{ post.excerpt }}
  {% if forloop.last == false %}<hr>{% endif %}
{% endfor %}
