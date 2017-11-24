---
layout: home
---
<h2>💩 archive 💩</h2>
{% for poop in site.data.trumps.poops %}
<p>Trump pooped at <b>{{ poop.location }}</b> in {{ poop.city }} on {{ poop.date | date: "%B %-d, %Y" }}</p>
{% endfor %}
