---
layout: home
---

<div class="boxes">

<div class="box box2">

confident idiots

A one-person games dev company no-one knows about.

</div>

{% for c in site.collections reversed %}
<div class="{{ c.label }} box">
[{{ c.label }}]({{ c.label }})
</div>
{% endfor %}

{% for i in (1..30) %}

<div class="box"></div>

{% endfor %}

</div>
