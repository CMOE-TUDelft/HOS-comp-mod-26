---
title: Week 5
layout: default
parent: Calendar
nav_order: 6
---

# Week 5

{% assign week_5 = site.modules | where: "path", "_modules/week-05.md" | first %}
{{ week_5.content | markdownify }}