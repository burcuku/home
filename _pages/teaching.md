---
layout: archive
title: 
permalink: /teaching/
author_profile: true
---

{% include base_path %}

## Current courses:

{% assign currentcourses = site.teaching | where: 'status', 'current' %}
{% for post in currentcourses reversed %}
  {% include archive-single.html %}
{% endfor %}

## Past courses:

{% assign pastcourses = site.teaching | where: 'status', 'past' %}
{% for post in pastcourses reversed %}
  {% include archive-single.html %}
{% endfor %}
