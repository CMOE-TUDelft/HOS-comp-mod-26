---
title: Week 2
layout: default
parent: Calendar
nav_order: 2
---

# Week 2

{% assign week_2 = site.modules | where: "path", "_modules/week-02.md" | first %}
{{ week_2.content | markdownify }}