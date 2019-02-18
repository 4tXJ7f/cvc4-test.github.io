---
layout: default
---

# People

## Project Leaders

[Clark Barrett](https://cs.stanford.edu/~barrett/) (Stanford University)<br />
I am a professor at Stanford University and a project leader for CVC4. I work
with all of the developers closely and have contributed code for a variety of
features, including the array theory solver, several preprocessing phases,
parts of the combination framework, and the model generation procedure.

[Cesare Tinelli](http://homepage.cs.uiowa.edu/~tinelli/) (University of Iowa)<br />
I'm a Professor of Computer Science at the University of Iowa and a project
leader for CVC4. I'm involved mainly in high level activities such as overall
design and new features and algorithms, and in the research behind them. I'm
also active in seeking and securing funding for CVC4's development from
governmental  agencies and through collaborations with industrial partners.

## Current Developers

{% assign sorted = site.data.people.devs | sort: 'lname' %}
{% for person in sorted %}
{% if person.website %}
[{{ person.fname }} {{ person.lname }}]({{ person.website }}) ({{ person.affiliation }})
{% else %}
{{ person.fname }} {{ person.lname }} ({{ person.affiliation }})
{% endif %}
{% endfor %}
