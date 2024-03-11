---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

As software systems have become ubiquitous in our lives, modern applications are designed to be highly concurrent, responsive, fault tolerant and distributed. Increased complexity of the software systems makes it more difficult to reason about possible behaviors of a system and to produce correct software. 


The research of my team aims to improve the reliability of software by building program analysis, testing and verification techniques. To this end, our research spans software engineering, formal methods, programming models and languages, concurrent programming, and distributed systems. 


## Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


**See more at [Google Scholar](https://scholar.google.com/citations?user=HwPJzFMAAAAJ&hl=en) and [DBLP](https://dblp.org/pid/148/1309.html)**