---
layout: default
title: Hackday Ideas
---
<p>
  Looking for something to work on? Here are some ideas from the community that
  may be useful!
</p>

<hr>

<ul>
{% for idea in site.data.ideas %}
  <li>
    <h3>{{ idea.name }}</h3>
    {{ idea.info }}
{% if idea.links %}
    <ul>
{% for link in idea.links %}
      <li><a href="{{ link }}" target="_blank">{{ link }}</a></li>
{% endfor %}
    </ul>
{% endif %}
  </li>
{% endfor %}
</ul>
