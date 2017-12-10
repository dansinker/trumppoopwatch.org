---
layout: home
---
<div id="archive">
  <h2>💩 Trump has pooped <span class="thecount"></span> times since taking office 💩</h2>
  <div class="list">
    {% for poop in site.data.trumps.poops %}
      <p class="poops">On {{ poop.date | date: "%B %-d" }}, Trump pooped at <b>{{ poop.location }}</b> in {{ poop.city }}. <a href="{{ poop.link }}">[source]</a></p>
    {% endfor %}
  </div>
</div>

<script>
var numItems = $('.poops').length;
$( ".thecount" ).append(numItems);
</script>
