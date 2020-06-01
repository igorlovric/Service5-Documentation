---
title: Basics
taxonomy:
    category: docs
child_type: docs
twig_first: true
process:
    twig: true
---

### Chapter 1

# Basics Stuff 12

Discover the **basic** principles

{% set langobj  = grav['language'] %}
{% set curlang  = langobj.getLanguage() %}
{{ curlang }}
{{ langobj.getDefault() }}