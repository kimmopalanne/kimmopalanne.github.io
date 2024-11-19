---
layout: archive
permalink: /research/
title: "Research"
author_profile: true
---




### Working Papers

{% include base_path %}
{% for post in site.research reversed %}
  {% if post.categories contains 'workingpaper' %}
  {% include archive-single.html %}
    {% endif %}
{% endfor %}

<hr class="new1">

### Publications

{% include base_path %}
{% for post in site.research reversed %}
  {% if post.categories contains 'journal' %}
  {% include archive-single.html %}
    {% endif %}
{% endfor %}

<hr class="new1">

### Policy work


{% include base_path %}
{% for post in site.research reversed %}
  {% if post.categories contains 'policy' %}
  {% include archive-single.html %}
    {% endif %}
{% endfor %}



