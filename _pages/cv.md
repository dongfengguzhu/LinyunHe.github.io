---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Mathematics and Applied Mathematics, Fudan University, 2017
* M.A. in Statistics, Columbia University, 2019
* Ph.D. in Industrial and Manufacturing Engineering, with Dual-title degree in Operations Research, Penn State University, 2023 (expected)

[//]: <> Work experience
[//]: <> ======
[//]: <> * Summer 2015: Research Assistant
[//]: <>   * Github University
[//]: <>   * Duties included: Tagging issues
[//]: <>   * Supervisor: Professor Git
[//]: <> 
[//]: <> * Fall 2015: Research Assistant
[//]: <>   * Github University
[//]: <>   * Duties included: Merging pull requests
[//]: <>  * Supervisor: Professor Hub

Papers
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* Languages: C++, R, Python
* Software: LaTeX, MATLAB.

[//]: <> Teaching
[//]: <> ======
[//]: <>   (<ul>{% for post in site.teaching %})
[//]: <>   (  {% include archive-single-cv.html %})
[//]: <>   ({% endfor %}</ul>, have to add the parentheses to make the comments)
[//]: <>  
[//]: <> Service and leadership
[//]: <> ======
[//]: <> * Currently signed in to 43 different slack teams
