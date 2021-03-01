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

# **What motivates Me**
It motivates me to tackle any programming issues on the most
fundamental/abstract level in order to not only fix the current issue but also
making the codebase I’m working with less error prone and more stable than it
was before the fix. I think this is the only way to achieve an improvement of
software quality in the long term. Thus, thinking about the larger context and
improving  the software design drives my motivation. I’m also happy to have the
possibility to learn new things everyday and keep me up to date with upcoming
trends with regards to new tooling, frameworks or programming languages.


<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
