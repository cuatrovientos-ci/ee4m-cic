---
title: eqf4
permalink: eqf4.html
layout: page
unit:
  course: "intro-operation-management"
  title: "eqf4"
  module: "000 Operation management"
---

{% assign modules = site.pages  %}
{% for module in modules  | sort  %}
[{{ module.course.title }}]({{ eqf.permalink }})
{% endfor %}
