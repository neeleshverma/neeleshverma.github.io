---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

* SRI International - Machine Learning Research Intern, Summer 2023 -->

* Samsung Research - Machine Learning Engineer, Aug 2020 - June 2022

* Samsung Research - Machine Learning Intern, Summer 2019

* Carnot Technologies - Software Engineer Intern, Summer 2018

{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}