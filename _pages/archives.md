---
layout: default
title: Archives
permalink: /archives/
---

<div class="page-container no-border">
	<h1>{{page.title}}</h1>
	<p>Past people, teams and projects at Columbia University.</p>
	<br>
	<h2>People</h2>
	<ul>
		{% for post in site.people %}
		{% if post.archive %}
		<a href="{{site.baseurl}}{{post.url}}"><li>{{post.title}}</li></a>
		{% endif %}
		{% endfor %}
		<li>Alex Gil</li>
	</ul>
</div>
