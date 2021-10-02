---
layout: default
title: Employers
---
This is a list of employers who've taken students on Fieldwork in past years. You'll have to do your own research to find out who to contact.

<ul class="employers columns3">
{% assign allEmployers = site.data.employers | sort: "employerName" %}
{% for employer in allEmployers %}
	<li class="employers"><a href="{{ employer.url }}" target="_blank">{{ employer.employerName }}</a></li>
{% endfor %}
</ul>