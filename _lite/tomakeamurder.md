---
layout: page
title: To Make a Murder
date: 2017-02-23 13:30:58
tags: experimental narrative mystery
img:  ToMakeAMurder.png
link: ToMakeAMurder.pdf
---

*... a narrative solo mystery framework*

More proof of concept than anything else, to be honest. It's a basic framework to run a mystery game; you start at the top and work your way down, playing out each scene and periodically uncovering key clues about the characters.

The clues are hidden in the back of the book, kind of like those old magic ink sleuthing books from the 80s.

<div class="img_row">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}"><img class="col three" src="{{ site.baseurl }}/img/{{ page.img}}" alt="" title="{{ page.title }}"/></a>
</div>
<div class="col three caption">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}">{{ page.title }}</a>
</div>

<br><br><br>
Click on the images below for a large size preview.

<div class="img_row">
	<a href="{{ site.baseurl }}/img/ToMakeAMurder_toc.png"><img class="col one" src="{{ site.baseurl }}/img/ToMakeAMurder_toc.png" alt="" title="Table of Contents"/></a>
	<a href="{{ site.baseurl }}/img/ToMakeAMurder_s1.png"><img class="col one" src="{{ site.baseurl }}/img/ToMakeAMurder_s1.png" alt="" title="Overview"/></a>
	<a href="{{ site.baseurl }}/img/ToMakeAMurder_x1.png"><img class="col one" src="{{ site.baseurl }}/img/ToMakeAMurder_x1.png" alt="" title="Scenario Excerpt"/></a>
</div>
<div class="col three caption">
	From left to right, the table of contents, an overview of play, and an example scene, <i>The Beginning</i>.
</div>

{% if page.aps.size > 0 %}

<h4>Actual Play & Reviews</h4>

<p></p>

<div>
	<ul style='padding-left: 0px; display: inline; list-style-type: none;'>
		{% for link in page.aps %}
			<li><a href="{{ link[1] }}">{{ link[0] }}</a></li>
			{% if forloop.last == false %}
	  	<i class="fa fa-ellipsis-v" aria-hidden="true"></i>
			{% endif %}
		{% endfor %}
	</ul>
</div>

{% endif %}
