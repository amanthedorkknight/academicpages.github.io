---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Find the pdf [here](/files/CV_5.0.pdf).

Education
======
* Ph.D. in Computer Science, University of Virginia, Ongoing 
* M.S. in Data Science, University of Virginia, 2019
* B.Tech. in Mechanical Engineering, IIT Roorkee, 2017

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
 -->