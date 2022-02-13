---
title: Iran 
layout: "index.njk"
---
<div class="desc">
Iran (Persia) is a large country located in the Midle East.<br/> Many ethnicities live in Iran, Includes Persian, Turkish, Kurdish, Lor, Arabic, Baluch, Mazani, Gilak, etc. <br/>The official language of Iran is Persian(Farsi).<br/> Iran has a very rich history and many early civilizations were formed in this land.<br/> In different provinces of Iran, you can see different climates and nature. The capital of Iran is Tehran.
</br>
<a href="https://en.wikipedia.org/wiki/Iran" target="_blank"> More information... </a>
 
<ul>
{% for post in collections.posts %}
<li>
<a href="{{ post.url }}">
    {{ post.data.title }}
</a>
</li>
{% endfor %}
</ul>
</div>
<!-- <figure><img src="./img/1.jpeg"></figure> -->
<!-- <figure><img src="./img/perspolis2.jpg"></figure> -->




