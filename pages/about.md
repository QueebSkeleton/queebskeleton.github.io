---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:.

I am a Full Stack Web Developer, more leaning on backend functionalities.
This involves both bringing up infrastructure to working condition,
and implementing features as planned to code. I also can transform
design specifications to actual user interfaces.

When I learn, I focus on the fundamentals rather than just the how-tos,
which enables me to learn new things without unnecessary difficulty.
This allows me to adapt to teams and fit in just as nicely.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
