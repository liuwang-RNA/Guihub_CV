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
* Visiting students in RNA biology, the State Key Laboratory of Biotherapy/West China of Hospital, 2022.02-2024.06, Supervisor: Prof. Zhaoming Su
* D.D.S in Endodontics, Stomatology, West China College of Stomatology, 2021.09-2024.06, Supervisor: Prof. Dingming Huang
* M.S. in Endodontics, Stomatology, West China College of Stomatology, 2017.09-2020.08, Supervisor: Prof. Dingming Huang
* B.S. in Stomatology, West China College of Stomatology, Sichuan University, 2012.09-2017.06

Work experience
======
* 2024.07-now: postdoctoral researcher
  * Sichuan University
  * Duties includes: leading independent research on bacterial non-coding RNAs, including structural–functional studies, project applications, and graduate student mentoring.
  * Supervisor: Prof. Zhaoming Su & Prof. Dingming Huang

* 2020.09-2021.08: research assistant
  * Sichuan University
  * Duties includes: assisted in project execution and management in bacterial RNA biology under supervisor’s guidance.
  * Supervisor: Prof. Dingming Huang
  
Skills
======
* Cryo-EM single particle analysis
* RNA modeling
* Genomic mining of RNA tools

Publications
======
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
