---
layout: photolist
title: Syllabus
menu: yes
---



# Lectures

{% assign lectures = (site.data.2018.lectures | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}


