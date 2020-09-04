---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Programme Committee
======
* *Nordsec 2019*
* *Cyberhunt 2019*
* *Nordsec 2018*
* *Cyberhunt 2018* 

Reviewer
======
* *International Conference on Machine Learning (ICML) 2020*
* *International Joint Conferences on Artificial Intelligence (IJCAI) 2019*
* *Norwegian Artificial Intelligence Society (NAIS) Symposium 2019*
* *MDPI Informatics*
