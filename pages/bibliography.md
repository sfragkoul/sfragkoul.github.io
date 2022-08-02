---
layout: base
title: Publications
permalink: /publications/
background: https://images.unsplash.com/photo-1470549638415-0a0755be0619?auto=format&w=2000
---

<!-- # Bibliography -->

[**Journals**](#journals) &nbsp; [**Conferences and Announcements**](#conferences-and-announcements) &nbsp; [**Thesis**](#thesis); 

<br/>


## Journals

<p style="margin-bottom:15px"></p>

### 2022

{% bibliography --query @article[year=2022] %}


<br/>

## Conferences and Announcements
<p style="margin-bottom:15px"></p>
### 2022
{% bibliography --query @inproceedings[year=2022] %}
{% bibliography --query @conference[year=2022] %}
<br/>




### Thesis

{% bibliography --query @phdthesis %}
{% bibliography --query @masterthesis %}


[//]: # {% bibliography --query @ \* [year=2017] %}
[//]: # (pandoc --filter=pandoc-citeproc --standalone publications.md -o publications.html)
