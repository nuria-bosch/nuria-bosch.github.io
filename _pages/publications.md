---
layout: page
permalink: /publications/
title: publications 📝
description: Feel free to email me for PDFs!
years:
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<p> 
All my research outputs divided into 
</p>


<p>
<ul>
    <li><a href="#manuscript"><b>Manuscripts</b></a></li>
    <li><a href="#journal"><b>Journal and edited volume articles</b></a></li>
    <li><a href="#proceedings"><b>Proceedings articles</b></a></li>
    <li><a href="#working"><b>Working papers</b></a></li>
    <li><a href="#theses"><b>Theses</b></a></li>
</ul>
</p>

<div class="publications">

<a id="manuscript"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;">Manuscripts</h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">
{% bibliography -f manuscripts %}

<a id="journal"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;">Journal articles</h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">
{% bibliography -f papers %}

<!--  <a id="manuscripts"><h3 style="margin-top: 3rem; margin-bottom: 0.3rem;">Manuscripts</h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;"> -->

<!-- <h2 class="year">Proceedings articles</h2><br><br> -->

<a id="proceedings"><h3 style="margin-top: 3rem; margin-bottom: 0.3rem;">Proceedings papers</h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">
  
{% bibliography -f proceedings %}

<a id="journal"><h3 style="margin-top: 3.3rem; margin-bottom: 0.3rem;">Working papers</h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">
{% bibliography -f workingpapers %}

<a id="theses"><h3 style="margin-top: 3rem; margin-bottom: 0.3rem;">Theses</h3></a>
<hr style="color: var(--global-text-color); height: 1px; margin-bottom: 2rem;">
  
{% bibliography -f theses %}

</div>

<div class="publications">
