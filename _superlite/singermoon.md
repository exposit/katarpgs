---
layout: superlite
title: Singer Moon
date: 2019-02-28 23:45:39
tags: [omgam, pbta, February, 2, 2019, cards]
img: SingerMoon.png
link: SingerMoon.pdf
title2: Singer Moon Cards
img2: SingerMoonCards.png
link2: SingerMoonCards.pdf
---

The second game of the "one microRPG game a month" challenge <a href="https://exposit.github.io/omgam/">OMGAM</a> for 2019.

This was an exercise in putting too much effort into one aspect of the game; I spent most of the month making oracle cards and not enough of it making an actual game.

So no theme, and no art, other than the <a href="">oracle cards</a>, and a very barebones riff on an unpublished Everway-inspired game I wrote a while back.

* Generic.
* Oracle cards.
* Can be used as a framework with any system, but is a system in itself.

<div class="img_row">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}"><img class="col three" src="{{ site.baseurl }}/img/{{ page.img}}" alt="" title="{{ page.title }}"/></a>
</div>
<div class="col three caption">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}">{{ page.title }}</a>
</div>

And here are the cards, ready to be printed and cut out.

<div class="img_row">
	<a href="{{ site.baseurl }}/pdf/{{ page.link2 }}"><img class="col three" src="{{ site.baseurl }}/img/{{ page.img2}}" alt="" title="{{ page.title2 }}"/></a>
</div>
<div class="col three caption">
	<a href="{{ site.baseurl }}/pdf/{{ page.link2 }}">{{ page.title2 }}</a>
</div>

<div style='margin-bottom: 2cm'>
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
