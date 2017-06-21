---
layout: page
title: challenge
permalink: /challenge/
navlink: challenge
---

{% for project in site.challenge %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ project.redirect }}" target="_blank">
        {% if project.img %}
        <img class="thumbnail" src="{{ site.baseurl }}/img/{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>

            <p>{{ project.tags | array_to_sentence_string }}</p>
        </span>
        </a>
    </div>
</div>
{% else %}

<div class="project ">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ site.baseurl }}/img/{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>

            <p>{{ project.tags | array_to_sentence_string }}</p>
        </span>
        </a>
    </div>
</div>

{% endif %}

{% endfor %}
