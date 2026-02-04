---
title: Weekly Schedule
description: The weekly event schedule.
nav_order: 2
---

# Weekly Schedule

Details about the schedule can be written here

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
