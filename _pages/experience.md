---
layout: archive
title: "Work Experience"
permalink: /experiences/
author_profile: true
---

{% include base_path %}

---

`PROFESSIONAL EXPERIENCE`
====

{% for post in site.experiences_industry reversed %}
  {% include archive-single.html %}
{% endfor %}

---

`INTERNSHIP EXPERIENCE`
====

{% for post in site.experiences_intern reversed %}
  {% include archive-single.html %}
{% endfor %}

---

`ACADEMIC JOB EXPERIENCE`
====

{% for post in site.experiences_acad reversed %}
  {% include archive-single.html %}
{% endfor %}