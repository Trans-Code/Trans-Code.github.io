---
layout: default
title: Past Events
---
Here are the event pages for a few of our past events...


<hr>

{% for event in site.data.events %}
<div>
  <h3>{{ event.name }}</h3>
  <p>
    <b><a href="{{event.page}}">{{event.location}}</a></b>
  </p>
  <p>{{event.date}}
 </p>
</div>

{% endfor %}

<hr>


