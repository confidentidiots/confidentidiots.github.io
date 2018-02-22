---
layout: home
permalink: /contumacious/index.html
---
<div class="boxes">

<div class="box box2">

Contumacious Commuter

</div>

{% for item in site.contumacious reversed %}
<div class="box altbox">
[{{ item.title }}]({{ item.url }})

<small>{{item.date | date: "%Y"}}</small>
</div>
{% endfor %}

{% for i in (1..30) %}

<div class="box"></div>

{% endfor %}


</div>
