---
layout: cv
title: CV
permalink: /cv/
---

Some information about you!

### My CV

A place to include any other types of information that you'd like to include about yourself.

### Contact me

[email@domain.com](mailto:email@domain.com)

<ul>
{% for job in site.data.work %}
  <li>
    <p>{{ job.timeframe }}</p>
    <p>{{ job.employer }}</p>
  </li>
{% endfor %}
</ul>
