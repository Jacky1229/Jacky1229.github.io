---
layout: archive
title: "Selected Projects"
permalink: /projects/
author_profile: true
---
  
## News Retrieval
* To distinguish the stand of the controversial news (written in Chinese) by using BM25 and Pseudo Relevance Feedback (PRF)
* Won **Second Prize** in 2019 Artificial Intelligence Cup, Taiwan<br/>
<img src='/images/projects/News_Retrieval.png' width='600' >

## Timing-Aware Fill Insertion
* Insert dummy fills based on proposed equivalent capacitance analysis to reduce potential timing degradation
* Won **Excellence Award** in CAD Contest, Taiwan
* Published in *ASP-DAC '20* <br/>
<img src='/images/projects/Dummy_Fill.png' width='400' >

## Pipelined MIPS design
* Final project of *Digital System Design* course <br/>
<img src='/images/projects/DSD_project.png' width='600' > <br/>

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
