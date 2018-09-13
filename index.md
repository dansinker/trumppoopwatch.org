---
layout: home
---
<h2>It has been <time class="timeago" datetime="{{ site.data.trumps.poops[0].date }}">{{ site.data.trumps.poops[0].date }}</time> since Trump's last 💩</h2>

  <p>His last visit to his own property was {{ site.data.trumps.poops[0].location }} in {{ site.data.trumps.poops[0].city }} on {{ site.data.trumps.poops[0].date | date: "%B %-d" }}. <a href="{{ site.data.trumps.poops[0].link }}">[source]</a></p>

{% assign counter = -1 %}
{% for poop in site.data.trumps.poops %}
 {% assign counter = counter | plus: 1  %}
{% endfor %}


  <p>Trump has pooped {{ counter }} other times too. <a href="/pooparchive.html">Check out the full poop count.</a></p>
