---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

My Google Scholar profile can be found [here](http://scholar.google.nl/citations?user=pKFkfq4AAAAJ).

<a href="#journals">Papers in international journals</a> |
<a href="#proc">Conference proceedings</a> |
<a href="#book">Book chapters</a> |
<a href="#abs">Abstracts</a> |
<a href="#theses">Theses</a>

<!-- _pages/publications.md -->
<div class="publications">

<h2><a id="journals"></a>Papers in international journals</h2>
{% bibliography --file papers %}
<h2><a id="proc"></a>Papers in conference proceedings</h2>
{% bibliography --file papers_conf %}
<h2><a id="abs"></a>Abstracts</h2>
{% bibliography --file papers_abstracts %}
<h2><a id="theses"></a>Theses</h2>
{% bibliography --file theses %}

</div>
