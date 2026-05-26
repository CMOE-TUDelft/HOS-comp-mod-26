---
title: Week 6
layout: default
parent: Calendar
nav_order: 7
---

# Week 6

{% assign week_6 = site.modules | where: "path", "_modules/week-06.md" | first %}
{{ week_6.content | markdownify }}