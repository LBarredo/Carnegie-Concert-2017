---
title: Program
order: 2
published: true
---
Tentative Program 

Ronen Shapira, Changing Reality #1: Spring
Vivaldi, Spring”
Villa-Lobos, Bachianas Brasileiras No. 5
Ronen Shapira, Changing Reality #2: Rhapsody in Blue
Gershwin, Rhapsody in Blue
Ronen Shapira, Changing Reality #3, Love and Despair

_Intermission_

Ronen Shapira, Changing Reality #4
PDQ Bach, Blaues Gras Cantata
Yotam Ben Or, The young generation
Ronen Shapira, Changing Reality #5: Strings of Peace

[comment]: <> (Do NOT edit.)
{% assign program = site.program | sort: 'order' %}
<ul class="performers">
{% for session in program %}
  <li>
  <h3 class="performer-name">{{ session.title }}</h3>
  {% if session.artist %}
  <h4 class="performer-focus">{{ session.artist }}</h4>
  {% endif %}
  {{ session.content }}
  </li>
{% endfor %}
</ul>
