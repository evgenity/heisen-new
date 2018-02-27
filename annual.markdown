---
title: Ануал
permalink: /annual/
layout: default
---

<div class="block-1">
    <div class="container ">
      <div class="row">
        <div class="twelve columns">
          <h1 class="describe-title">{{page.title}}</h1>
			<div class="posts ">
          		{% for page in site.pages %}  
          			<li>
            			<a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a>
          			</li>
				{% endfor %}
    		</div>
		</div>
	</div>
</div>
