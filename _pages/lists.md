---
layout: listhome
title: lists
permalink: /lists/
lists: true  # includes a list of lists items
description: Lists of things I enjoy
nav: true
nav_order: 2
horizontal: false
---

{% if page.lists and site.announcements.enabled -%}
{%- include lists.html limit=true %}
{%- endif %}
