---
layout: page
title: Showcase
permalink: /showcase/
---

# This page is under construction

We're currently working on how to showcase stuff that we've built :) You can simply ask us for some more info on our past projects.

[Get Started](https://calendly.com/sils){:.c-btn}

Because we don't want to leave you hanging, we're collecting a couple of screenshots of stuff that we've done here :)

{% assign showcase_files = site.static_files | where: "showcase", true %}
{% for myimage in showcase_files %} ![]({{ myimage.path | absolute_url }}) {% endfor %}

[Get Started](https://calendly.com/sils){:.c-btn}