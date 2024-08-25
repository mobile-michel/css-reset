---
title: Home
layout: default
tags: primary
date: 2024-01-01
---
## Normalization Libraries

{% assign library = reset | where: 'category', 'normalization' %}
{% for item in library %}
- [{{ item.name }}](/paginate/{{ item.name | slug }}/index.html) by {{ item.author }}
{% endfor %}

## CSS Reset

{% assign library = reset | where: 'category', 'reset' %}
{% for item in library %}
- [{{ item.name }}](/paginate/{{ item.name | slug }}) by {{ item.author }}
{% endfor %}

## Articles

[5 Best CSS Reset/Normalization Libraries](https://krdevnotes.com/5-best-css-reset-normalization-libraries/#:~:text=CSS%20Normalization,-Just%20like%20CSS&text=The%20goal%20of%20a%20normalization,is%20consistent%20across%20different%20browsers.)

## Searches

- [CSS Normalization Libraries](https://www.google.ch/search?q=CSS+Normalization+Libraries)
- [CSS reset](https://www.google.ch/search?q=css+reset)