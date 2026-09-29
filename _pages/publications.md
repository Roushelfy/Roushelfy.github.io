---
layout: archive
title: "Publications"
permalink: /publications/
description: "Publications and preprints by Zhaofeng Luo on physics simulation, GPU contact solvers, MPM, and robotic manipulation."
author_profile: true
---

## Papers and Preprints

{% for post in site.publications reversed %}
  {% unless post.resource %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

## Software and Educational Resources

{% for post in site.publications reversed %}
  {% if post.resource %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
