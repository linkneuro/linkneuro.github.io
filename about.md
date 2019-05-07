---
layout: page
title: About
permalink: /about/
---

### Tags

{% assign tags = page.tags | split:&nbsp; %}
<ul>
    {% for tag in tags %}
    <li>{{ tag }}</li>
    {% endfor %}
</ul>
