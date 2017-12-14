---
layout: page
title: Showcase
permalink: /showcase/
---

# This page is under construction

We're currently working on how to showcase stuff that we've built :) You can simply ask us for some more info on our past projects.

[Get Started](https://calendly.com/sils){:.c-btn}

Because we don't want to leave you hanging, we're collecting a couple of quotes and screenshots of stuff that we've done here :)

{% assign showcase_files = site.static_files | where: "showcase", true %}
{% for myimage in showcase_files %} ![]({{ myimage.path | absolute_url }}) {% endfor %}

> Viperdev's competence and access to broad development resources make it the perfect one stop shop for developing an MVP. They have answers to questions you don't even know to ask.

*Cynthia Wandia, CEO of Aerupt Ltd*

> Highly competent and efficient. Very smooth to work with.

*Prof. Dr. Christoph Ihl, TUHH Institute of Entrepreneurship*

> The team's response time was mind blowing - I could get any question answered within minutes!

*Viktoria Boss, Researcher*

[Get Started](https://calendly.com/sils){:.c-btn}