---
layout: default
title: Past Events
---
Here are the event pages for a few of our past events...


<hr>

{% for event in site.data.events %}
<div>
  <h3>{{ event.name }}</h3>
  <p><a href="{{event.page}}">{{event.date}}</a>
 </p>
</div>

{% endfor %}

<hr>


