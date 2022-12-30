---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** ,<br>
I am a Ph.D. level researcher at MIT Lincoln Laboratory and Georgia Institute of
Technology looking to transition to business.
<div class="row">
{% include about/skills.html title="Research Skills" source=site.data.research-skills %}
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
