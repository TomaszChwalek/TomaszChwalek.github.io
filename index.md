---
# layout: splash
permalink: /
layout: single
author_profile: true
#title: Home
---

## About

I am a PhD student in Data Science at IT University of Copenhagen.
My research focuses on [brief description of your research topics].
I am interested in [areas of interest or keywords].

## Publications

{% if site.publications %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
  <p>No publications found. Make sure you have a _publications folder with publication files.</p>
{% endif %}

