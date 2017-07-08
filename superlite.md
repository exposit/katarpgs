---
layout: page
title: superlite
permalink: /superlite/
navlink: superlite
---

{% for project in site.superlite | reverse %}

{% if project.redirect %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}/pdf/{{ project.redirect }}" target="_blank">
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
