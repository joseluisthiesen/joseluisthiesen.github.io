---
layout: page
permalink: /publications/
title: publications
description: publications in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Journal Articles</h2>

{% bibliography --query @article %}

<h2 class="bibliography">Conference Proceedings</h2>

{% bibliography --query @inproceedings %}

</div>
