---
layout: page
title: Lab
permalink: /lab/
description: A growing collection of my cool projects.
---

{% for project in site.projects reversed %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <div class="project_image">
            <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>  
            <h1>{{ project.title }}</h1>
        </div>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
        {% if project.img %}
        <div class="project_image">
            <img class="thumbnail" src="{{ project.img | prepend: site.baseurl | prepend: site.url }}"/>  
            <div class="thumbnail-text">{{ project.title }}</div>
        </div>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}
