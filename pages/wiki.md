---
layout: page
title: Wiki
description: 速查手册
keywords: 维基, Wiki
comments: false
menu: 维基
permalink: /wiki/
---

> 好记性不如个烂笔头

<ul class="listing">
{% for wiki in site.wiki %}
{% if wiki.title != "Wiki Template" %}
<li class="listing-item"><a href="{{ wiki.url }}">{{ wiki.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
