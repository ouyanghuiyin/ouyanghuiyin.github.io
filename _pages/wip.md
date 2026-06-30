---
layout: archive
title: "Working Papers"
permalink: /wip/
author_profile: true
---

{% include base_path %}

{% for post in site.working_papers reversed %}
  {% include archive-single.html %}
{% endfor %}
