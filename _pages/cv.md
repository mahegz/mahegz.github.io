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
* B.S. in [Mathematics and Information Engineering(MIE)](https://www.ie.cuhk.edu.hk/programmes/bsc-in-mieg/), CUHK, 2018-2022 
  * Graduated from the ELITE stream with First Honours 
* [PhD-Track](https://www.ip-paris.fr/en/education/phd-track-applications-open-october-5th-january-12th-2024) in Data and AI (Mathematics), IP-Paris
  * M1 in Data and AI, 2023
  * M2 Mathématiques, Vision, Apprentissage (MVA)


Work experience
======

* Student Research (2023-Ongoing)

 Under the supervision of Prof. Aymeric Dieuleveut at CMAP, Polytechnique. I am working on research projects related to federated optimization. In particular, this work tackles methods of leverag new compression schemes to achieve differential privacy, Langevin dynamics, and smoothing. In addition, I am also working on new algorithms extending the gradient-based aggregation schemes used in federated optimization to optimization problems that are no inherentely gradient-based such as EM algorithms. 

* Summer 2021: Research Intern, Information Engineering Dept, CUHK

Working with Prof. Cheuk Ting Li, this project aimed to develop channel synthesis schemes for additive noise channels under finite blocklength. The current focus is analyzing the relationship between the achievable bit rate and the additive noise distribution. A paper has been published at the Information Theory Workshop Conference.

* Summer 2020: Research Intern, [MLO](https://www.epfl.ch/labs/mlo/), EPFL 

Under the supervision of Prof. Martin Jaggi, Dr Mary-Anne Hartley, and Dr Sai Karimireddy, I participated in machine learning research endeavours to explore methods of personalized federated learning. This project leveraged a multi-task learning viewpoint of constructing a similarity matrix between clients which is then used to infer clients' relations for gradient sharing. 
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications %}
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
* Currently signed in to 43 different slack teams -->
