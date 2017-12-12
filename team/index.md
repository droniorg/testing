---
title: Our Team
hero: Our Team
---

<ul class="staff">
	{% for person in site.staff_members %}
		<li>
			<div class="staff-image" style="background-image: url({% include relative-src.html src=person.image_path %})"></div>
			<div class="name">{{ person.name }}</div>
		</li>
	{% endfor %}
</ul>
