---
layout: page
permalink: /publications/
title: Publications
description: Papers, preprints and theses.
nav: true
published: true
nav_order: 2
---

<!-- Sections are selected by BibTeX entry type in _bibliography/papers.bib; rows are rendered by _layouts/pub_rows.liquid -->

{% include bib_search.liquid %}

<div class="publications pub-rows">

<h3 class="pub-section">Papers &amp; preprints</h3>
{% bibliography --query @article --template pub_rows %}

<h3 class="pub-section">In preparation</h3>
{% bibliography --query @unpublished --template pub_rows %}

<h3 class="pub-section">Theses</h3>
{% bibliography --query @mastersthesis --template pub_rows %}

</div>
