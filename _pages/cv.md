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
* M.Tech. in Computer Science and Engineering, Indian Institute of Science, Bangalore, 2018-2020
* B.Tech. in Computer Science and Engineering, MAKAUT, West Bengal, 2014-2018

Work experience
======
* September 2022 - present: Senior Silicon Design Engineer at AMD India
  * Working in SPG team.
  * Worked on performance debugging and benchmarking for AMD server platforms.


* August 2020 - September 2022: Member of Technical Staff 3 at Nutanix India
  * Worked in AHV (hypervisor) team on libvirt/qemu/KVM stack.
  * Worked on projects in hypervisor memory management, observability, live migrations.
  * Worked on local live migration (KVM Forum 2021).
  
* March 2017 - July 2020: Technical Co-Founder at Drivers4Me
  * Worked to develop the web server and mobile applications for the MVP of [Drivers4Me](https://www.drivers4me.com).

Skills
======
* Programming Languages: C, C++, Python
* Simulators: Sniper, gem5

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
