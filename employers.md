---
layout: default
name: employers
---
<ul class="employers">
{% for employer in site.data.employers %}
	<li class="employerName">{{ employer.employerName }}</li>
	<li class="contactName">{{ employer.contactName }}</li>
	<li class="web-site">{{ employer.web-site }}</li>
	<li class="email">{{ employer.email }}</li>
	<li class="streetAddress">{{ employer.streetAddress }}</li>
{% endfor %}
</ul>