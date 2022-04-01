---
layout: archive
permalink: /
title: "Bang Ming Yong"
---

<!-- ![test image Dogepig]({{site.baseurl}}/images/Bang_profile_40p.jpg) -->
<div style="background-color:black;color:white;padding:20px;">
	<img style="border-radius: 50px; float: right; width: 50%" src="/images/Bang_profile_40p.jpg" alt="Bang Ming Yong profile">
</div>
# Awards

<div class="tiles">
{% for post in site.posts %}
	{% if post.categories contains "portfolio" %}
		{% include post-grid.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->

# Latest thoughts

<div class="tiles">
{% for post in site.posts %}
	{% if post/categories contains "article" %}
		{% include post-grid.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->
