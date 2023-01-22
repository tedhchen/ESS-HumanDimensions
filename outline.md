---
layout: page
title: Outline
nav_order: 2
description: Listing of course modules and topics.
---

# Course Outline

Required readings should be completed before the corresponding class; they are designed to facilitate your understanding of the week's topic and to help with class discussions and your projects. Additional materials are optional resources for you; we do not expect you to read all the additional materials, but dive into the ones that interest you.

## Weekly Schedule

{% assign outline = site.modules | where: 'type', 'outline' %}
{% for module in outline %}
{{ module }}
{% endfor %}
