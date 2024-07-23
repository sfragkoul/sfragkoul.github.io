---
layout: base
title: Publications
permalink: /publications/
background: /assets/img/groupLogo/publications.jpg
---

<!-- # Bibliography -->

[**Book Chapters**](#book-chapters) &nbsp; [**Journals**](#journals) &nbsp; [**Conferences and Announcements**](#conferences-and-announcements) &nbsp; [**Other**](#other) &nbsp; [**Theses**](#theses)

<br/>

## Book Chapters

<p style="margin-bottom:15px"></p>

{% bibliography --query @inbook %}


<br/>

## Journals

<p style="margin-bottom:15px"></p>

{% bibliography --query @article %}


<br/>

## Conferences and Announcements
<p style="margin-bottom:15px"></p>

{% bibliography --query @inproceedings %}
{% bibliography --query @conference %}

<br/>

## Other
<p style="margin-bottom:15px"></p>

{% bibliography --query @misc %}

<br/>


## Theses

{% bibliography --query @phdthesis %}
{% bibliography --query @masterthesis %}


[//]: # {% bibliography --query @ \* [year=2017] %}
[//]: # (pandoc --filter=pandoc-citeproc --standalone publications.md -o publications.html)
