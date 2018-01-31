---
layout: page
title: Spider's Web
modified: 2017-07-11 20:10:34
tags: [game chef, d6s, choice]
img:  SpidersWeb.png
link: SpidersWeb.pdf
---

Spider’s Web is inspired by shows like Leverage and Charlie’s Angels, books like Modesty Blaise, and movies like Mission Impossible.

The design of Spider’s Web was influenced by Otherkind dice, My Life With Master, the Mythic Game Master Emulator, and some design talk on /r/rpgdesign.

You play Spider, a spymaster with three agents at your disposal -- but you'll have to manage them carefully if you want them to stay loyal and complete the mission.

<div class="img_row">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}"><img class="col three" src="{{ site.baseurl }}/img/{{ page.img}}" alt="" title="{{ page.title }}"/></a>
</div>
<div class="col three caption">
	<a href="{{ site.baseurl }}/pdf/{{ page.link }}">{{ page.title }}</a>
</div>

<br><br><br>
Click on the images below for a large size preview.

<div class="img_row">
	<a href="{{ site.baseurl }}/img/SpidersWeb_toc.png"><img class="col one" src="{{ site.baseurl }}/img/SpidersWeb_toc.png" alt="" title="Table of Contents"/></a>
	<a href="{{ site.baseurl }}/img/SpidersWeb_s1.png"><img class="col one" src="{{ site.baseurl }}/img/SpidersWeb_s1.png" alt="" title="Overview"/></a>
	<a href="{{ site.baseurl }}/img/SpidersWeb_c1.png"><img class="col one" src="{{ site.baseurl }}/img/SpidersWeb_c1.png" alt="" title="Character Sheet"/></a>
</div>
<div class="col three caption">
	From left to right, the table of contents, the overview page and a setting excerpt.
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
