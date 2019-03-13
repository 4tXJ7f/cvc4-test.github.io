---
layout: default
---

# Publications

{% assign years = site.data.publications.references | map: "issued" | map: "year" | uniq | sort | reverse %}
{% for year in years %}
## {{ year }}

{% assign yearStr = year | append: "" %}
{% assign yearInt = year | plus: 0 %}
{% assign refs = site.data.publications.references | where_exp: "ref","ref.issued[0].year == year" %}

{% for item in refs %}

{% for cauthor in item.author %}{{ cauthor.given }} {{ cauthor.family }}{% if forloop.last == false %}, {% endif %}{% endfor %}. {% if item.URL %}[{{ item.title }}]({{ item.URL }}){% else %}{{ item.title }}{% endif %}. In _{{ item.container-title }}_, {{ item.issued[0].year }}.<br />
{% if item.URL %}[[PDF]({{ item.URL }})]{% endif %} {% if item.DOI %}[[DOI](http://dx.doi.org/{{ item.DOI }})]{% endif %}

{% endfor %}

{% endfor %}

