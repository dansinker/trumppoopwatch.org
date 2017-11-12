---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
<h1>{{ site.title }}</h1>

  <h2>It has been {{ site.data.trumps.poops[0].date | timeago }} since Trump's last 💩</h2>
  <h3>His last 💩 was at the {{ site.data.trumps.poops[0].location }} on {{ site.data.trumps.poops[0].date | date: "%B %-d" }}.</h3>
