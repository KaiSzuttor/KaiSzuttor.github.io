---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>
I'm a C++ and Python developer from Stuttgart with a background in
computational soft matter science. In my leisure time I like to learn new
things about programming trends, riding the bicycle, playing the guitar and
having a good time with my two daughters.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
