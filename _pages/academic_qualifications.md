---
layout: archive
title: "Academic Qualifications"
permalink: /academic_qualifications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.academic_qualifications reversed  %}
   {% include archive-single-education.html %}
{% endfor %}
