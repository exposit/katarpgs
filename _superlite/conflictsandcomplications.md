---
layout: page
title: Conflicts & Complications
date: 2017-06-21 13:08:05
tags: [omgam, two dice, June, d6s]
img: ConflictsandComplications.png
link: ConflictsandComplications.pdf
title2: The Serpent's Eye Adventure
img2: TheSerpentsEye.png
link2: TheSerpentsEye.pdf
---

The first game of my "one microRPG game a month" challenge; a two d6 attempt at combining oracle and game into one information-packed roll.

* Very simple and easy to run without notes.
* One mechanic for resolving conflicts, pushing the story forward, and the oracle.
* Uses a simple Lenormand tarot inspired keyword chart.
* Strongly narrative with a few structure board game elements.
* Could easily be played with an experienced group, not just solo.

<div class="img_row">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}"><img class="col three" src="{{ site.baseurl }}/img/{{ page.img}}" alt="" title="{{ page.title }}"/></a>
</div>
<div class="col three caption">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}">{{ page.title }}</a>
</div>

I also wrote a companion adventure in a loose "CYOA" format; it's mostly system agnostic and plays into the example game in *Conflicts & Complications*. It's also highly experimental; an attempt to control the narrative while allowing plenty of room for standard solo improvisation.

I was trying to go for a companion format for C&C that would be easily moddable but I don't think this is it!

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
