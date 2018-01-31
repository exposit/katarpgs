---
layout: page
title: The Calypso Compendium
modified: 2017-03-13 16:53:51
tags: [pbta, lady blackbird, d6s]
img:  TheCalypsoCompendium.png
link: TheCalypsoCompendium.pdf
---

*... Apocalypse World mashed with Lady Blackbird*

A mashup of *Apocalypse World's* mechanics and *Lady Blackbird's* character generation, along with a heaping helping of general soloing techniques, run through the blender of my idiosyncratic play style.

*Calypso* is designed to be compatible with *Apocalypse World* and its derivatives. It should be trivial to use the core rules with any PbtA game, and the character options should work with Lady Blackbird with very little tweaking.

<div class="img_row">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}"><img class="col three" src="{{ site.baseurl }}/img/{{ page.img}}" alt="" title="{{ page.title }}"/></a>
</div>
<div class="col three caption">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}">{{ page.title }}</a>
</div>

<br><br><br>
Click on the images below for a large size preview.

<div class="img_row">
	<a href="{{ site.baseurl }}/img/TheCalypsoCompendium_toc.png"><img class="col one" src="{{ site.baseurl }}/img/TheCalypsoCompendium_toc.png" alt="" title="Table of Contents"/></a>
	<a href="{{ site.baseurl }}/img/TheCalypsoCompendium_s1.png"><img class="col one" src="{{ site.baseurl }}/img/TheCalypsoCompendium_s1.png" alt="" title="Overview"/></a>
	<a href="{{ site.baseurl }}/img/TheCalypsoCompendium_x1.png"><img class="col one" src="{{ site.baseurl }}/img/TheCalypsoCompendium_x1.png" alt="" title="Scenario Excerpt"/></a>
</div>
<div class="col three caption">
	From left to right, the table of contents, the overview page and an excerpt from the scenario <i>Darkness Falls</i>.
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
