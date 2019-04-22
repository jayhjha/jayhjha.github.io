---
layout: home
permalink: /
image:
  feature: sea-to-summit.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
