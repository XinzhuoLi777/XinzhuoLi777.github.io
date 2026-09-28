---
layout: page
permalink: /publications/
title: Publications
description: Papers and preprints on database theory and data management.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<!-- Author-order legend: author_order={alphabetical} in papers.bib adds † to every author; "Li*, Xinzhuo" marks equal contribution -->
<p class="pub-legend">
  <span><span class="pub-mark">†</span> alphabetical author order, equal contribution (theory papers)</span>
  <span><span class="pub-mark">*</span> equal contribution</span>
  <span>otherwise, authors are listed by contribution</span>
</p>

<div class="publications">

{% bibliography %}

</div>
