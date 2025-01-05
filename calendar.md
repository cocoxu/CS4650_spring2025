---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

**A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1uSY7PnbjWw-RY6hq7PO_-uBjd1d3wItyJEbgZEMZoRI/edit?usp=sharing).**


{% for module in site.modules %}
{{ module }}
{% endfor %}
