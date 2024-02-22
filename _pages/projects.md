---
layout: archive
title: "Research"
permalink: /projects/
author_profile: true
---


<style>
a:link {
  text-decoration: none;
}
</style>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}