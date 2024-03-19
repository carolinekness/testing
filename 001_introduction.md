---
layout: default
title: Introduction
number: 001
---
# Introduction

**This is my introduction page.**[^1] My project includes a variety of different sources.

{% assign intro_images = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'introduction'" | where_exp: "item", "item.media_type == 'image'" %}
{% include media.html pages=intro_images %}


Voilà! Let's see if putting this text below assign intro images impacts anything.[^2]

[^1]: first footnote 
[^2]: I copied this text from this [website](https://www.lipsum.com/feed/html) 
