---
title: Week 3
layout: default
parent: Calendar
nav_order: 4
---

# Week 3

{% assign week_3 = site.modules | where: "path", "_modules/week-03.md" | first %}
{{ week_3.content | markdownify }}