---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
<div id="titlebox">
<!-- <h1>{{ site.title }}</h1> -->
<h1>Trump <span class="whee">💩</span><span class="clear">Watch</span></h1>
<p>{{ site.description | escape }}</p>
</div>

<h2>It has been <time class="timeago" datetime="{{ site.data.trumps.poops[0].date }}">{{ site.data.trumps.poops[0].date }}</time> since Trump's last 💩</h2>

  <p>His last visit to his own property was {{ site.data.trumps.poops[0].location }} on {{ site.data.trumps.poops[0].date | date: "%B %-d" }}. <a href="{{ site.data.trumps.poops[0].link }}">[source]</a></p> 
