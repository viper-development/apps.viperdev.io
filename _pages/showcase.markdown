---
layout: page
title: Showcase
permalink: /showcase/
---

# This page is under construction

We're currently working on how to showcase stuff that we've built :)

Because we don't want to leave you hanging, we're collecting a couple of screenshots of stuff that we've done here :)

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  ![]({{ myimage.path | absolute_url }})
{% endfor %}