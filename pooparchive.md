---
layout: home
---
<div id="archive">
  <h2>💩 archive 💩</h2>
  <div class="list">
    {% for poop in site.data.trumps.poops %}
      <p>On {{ poop.date | date: "%B %-d" }}, Trump pooped at <b>{{ poop.location }}</b> in {{ poop.city }}. <a href="{{ poop.link }}">[source]</a></p>
    {% endfor %}
  </div>
</div>
