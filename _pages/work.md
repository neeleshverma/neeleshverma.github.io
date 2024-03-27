---
layout: archive
title: "Work Experience"
permalink: /work/
author_profile: true
---

{% include base_path %}

* <ins>**SRI International** - _Machine Learning Research Intern, Summer 2023_</ins>  
  I did an internship with [SRI International](https://www.sri.com/) as an ML Researcher in the [Neuro-Symbolic Computing and Intelligence (NuSCI)](https://nusci.csl.sri.com/)  Research Group. I worked on the Robust ML side, specifically, localizing and detecting physical adversarial patches in the frequency domain.

  
* <ins>**Samsung Research** - _Software Engineer - Machine Learning, Aug 2020 - June 2022_</ins>  
  I started my full-time at [Samsung Research Institute](https://research.samsung.com/sri-b) as a Software Engineer - Machine Learning in the Computer Vision for Devices group. I was involved with the [Penup](https://www.penup.com/main/home) team where I worked on a GAN-based model for artwork generation, improving image stylization latency and quality, weekly Supervised Object Detection, etc.

  
* <ins>**Samsung Research** - _Software Engineer Intern - Machine Learning, Summer 2019_</ins>  
  In the summer of 2019, I got an opportunity to work with [Samsung Research Institute](https://research.samsung.com/sri-b) as a Software Intern - Machine Learning. I worked in the [Penup](https://www.penup.com/main/home) team on controlled [Artistic Style Transfer](https://paperswithcode.com/task/style-transfer) for an artwork dataset.

  
* <ins>**Carnot Technologies** - _Software Engineer Intern, Summer 2018_</ins>  
  My first work experience in the industry started with [Carnot Technologies](https://www.carnot.co.in/) as a Software Intern. It was a small startup back then. I got a chance to work on a tractor analytics app - [Simha](https://play.google.com/store/apps/details?id=com.carnot.traclytics.simha), that we deployed later on Android.

{% for post in site.work reversed %}
  {% include archive-single.html %}
{% endfor %}
