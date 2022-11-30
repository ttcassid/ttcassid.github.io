---
layout: archive
title: "Application Materials"
permalink: /applicationmaterials/
author_profile: true
redirect_from:
  - /jobmaterials
---

{% include base_path %}
 Fellowships during graduate school
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Postdoctoral fellowships 
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Academic and Industrial Job Search
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  