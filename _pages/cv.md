---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Please download CV [from here](https://prachatos.github.io/files/PrachatosCV.pdf).

Education
======
* Ph.D. in Computer Science, Georgia Institute of Technology, Atlanta, GA, 2023 - (ongoing)
* M.Tech. in Computer Science and Engineering, Indian Institute of Science, Bangalore, 2018-2020
* B.Tech. in Computer Science and Engineering, MAKAUT, West Bengal, 2014-2018

Research
======
* 2026 - present: Resource allocation and scheduling for actor-based workloads on commodity hardware, Georgia Tech
* 2023 - present: Design and simulation for an actor-model sparse graph processing architecture, Georgia Tech (IARPA AGILE)
  * MacroPattern, a methodology that abstracts actor-model workloads into fitted statistical distributions per handler and scales them analytically to arbitrary problem and system size.
  * MPSim, an SST-based parallel discrete-event simulator that takes those distributions as input and simulates systems of ~16 million processing elements.

Work experience
======
* September 2022 - December 2022: Senior Silicon Design Engineer at AMD India
  * Server Performance Group.
  * Profiled networking and virtualization workloads on EPYC Bergamo servers, attributing throughput loss to OS interrupt handling overhead.


* August 2020 - September 2022: Member of Technical Staff 3 at Nutanix India
  * Worked in AHV (hypervisor) team on libvirt/qemu/KVM stack.
  * Worked on projects in hypervisor memory management, observability, live migrations.
  * Worked on local live migration (KVM Forum 2021).
  
* March 2017 - July 2020: Technical Co-Founder at Drivers4Me
  * Worked to develop the web server and mobile applications for the MVP of [Drivers4Me](https://www.drivers4me.com).

Skills
======
* Programming languages: C, C++, Python
* Performance: perf, PAPI, hardware counters
* Simulation: SST, gem5, Sniper

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

Service
======
* Artifact Evaluation Committee, ASPLOS 2027
