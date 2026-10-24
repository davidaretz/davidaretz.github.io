---
layout: page
title: Talks
permalink: /talks/
description: Research talks, posters and expository talks.
nav: true
nav_order: 3
---

{% comment %}Talks are edited in \_data/talks.yml.{% endcomment %}

<div class="talk-jump"><a href="#research">Research talks</a> <a href="#posters">Posters</a> <a href="#expository">Expository talks</a></div>

<h3 id="research" class="talk-section">Research talks</h3>
{% include talks_table.liquid items=site.data.talks.research %}

<h3 id="posters" class="talk-section">Posters</h3>
{% include talks_table.liquid items=site.data.talks.posters %}

<h3 id="expository" class="talk-section">Seminar &amp; expository talks</h3>
{% include talks_table.liquid items=site.data.talks.expository %}
