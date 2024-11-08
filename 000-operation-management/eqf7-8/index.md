---
title: eqf7-8
permalink: eqf7-8.html
layout: page
unit:
  course: "intro-operation-management"
  title: "eqf7-8"
  module: "000 Operation management"
---

{% assign modules = site.pages  %}
{% for module in modules  | sort  %}
[{{ module.course.title }}]({{ eqf.permalink }})
{% endfor %}
