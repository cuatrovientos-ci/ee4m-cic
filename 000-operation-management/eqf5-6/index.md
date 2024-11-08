---
title: eqf5-6
permalink: eqf5-6.html
layout: page
unit:
  course: "intro-operation-management"
  title: "eqf5-6"
  module: "000 Operation management"
---

{% assign modules = site.pages  %}
{% for module in modules  | sort  %}
[{{ module.course.title }}]({{ eqf.permalink }})
{% endfor %}
