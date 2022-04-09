---
layout: archive
title: "经验交流"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}


<ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

病例分享
========

<ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

谈心分享
========

<ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
