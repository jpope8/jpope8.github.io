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
* Ph.D in Information Technology, George Mason University, 2016
* M.S. in Telecommunications, George Mason University, 2010
* B.S. B.A in Information Systems, Auburn University at Montgomery, 1995

Work experience
======
* Spring 2022: Senior Lecturer in Data Science
  * University of Bristol
  * Duties includes: Teaching, Research, Admin

* Spring 2021: Senior Research Associate in Cybersecurity for IoT
  * University of Bristol
  * Duties included: Embedded Programming, Machine Learning Design/Development

* Summer 2016: Research Associate in IoT for E-Health
  * University of Bristol
  * Duties included: Wearable/Embedded Programming, BLE Network Programming
  
Skills
======
* Python
  * PyTorch
  * TensorFlow
  * Scikit-Learn
* Java
  * Weka ML Workbench
* Flutter/Dart
* Databases
  * Relational (Oracle, MS SQL Server)
  * Non-relatational (Cassandra, MongoDB)
* Operating Systems
  * Contiki-OS
  * Linux

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

