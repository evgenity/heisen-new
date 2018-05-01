---
title: Проекты
date: 2018-05-01 18:38:00 +03:00
permalink: "/projects/"
layout: page
---

{% for project in site.projects %}

<div class="project-card">
    <img src="{{ project.logo-url }}" />
    <h1> {{project.name}} </h1>
    <p>
        {{project.content}}
    </p>
    <p>{{project.date}}</p>
</div>

{% endfor %}

<style>
.project-card {
    background-color: grey;
    height: 200px;
    width: 200px;
    margin: 20px;
    display: block;
}
</style>