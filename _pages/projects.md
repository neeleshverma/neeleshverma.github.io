---
layout: archive
title: "Key Projects"
permalink: /projects/
author_profile: true
---

<style>
a:link {
  text-decoration: none;
}
</style>

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}