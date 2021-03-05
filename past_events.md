---
layout: default
title: Past Events
---
Here are the event pages for a few of our past events...


<hr>

{% for event in site.data.events %}
<div>
  <ul>
  <li>
  <h3>{{ event.name }}</h3>
    <a href="{{event.page}}">{{event.location}}</a>
<br/>
    {{event.date}}
    </li> 
  </ul>



{% endfor %}

<hr>


