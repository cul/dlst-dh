---
layout: default
title: Archives
permalink: /archives/
---

<div id="container" class="prose">
	<h1>{{page.title}}</h1>
	<p>Past people, teams and projects at Columbia University.</p>
	<h2>People</h2>
	<ul>
		{% for post in site.people %}
		{% if post.archive %}
		<li>{{post.title}}</li>
		{% endif %}
		{% endfor %}
	</ul>
</div>
